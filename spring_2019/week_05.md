## Last Week's Accomplishments

-VM issues: I figured out Google VM's are probably not the best platform for hosting a server for a large video game. There were no 'bugs', in reality the VM just was not made for what I was trying to get it to do.
-The only thing that this VM has is a GPU and a core for running the game. 

-I tested that a camera taking a still photograph of a 'mountain', brought the CPU usage to about 70%, if the camera rotates then the CPU usage caps to 100% on the VM.
-I was able to get the networking to work, however the 'game' consisted of two players remotely controlling spheres in a box. This also was almost always at th 100% limit. 
	-Running the server 'headless' is still an idea...
	->"d.exe -batchmode" Ran the program headless; now how to click the button in game from the weird black terminal thing.

## This Week's Plan

-Next time I return to my neighborhood, I will test to see if my "LAN" is truly LAN and attempt to connect 2 computers on different wifi networks. This will probably be pointless since the numbers you type into client IP change based on the wifi you are connected to and I do not see how this will work between two different wifi connections.

-Continue looking into options for hosting this 'server'. Once an option seems to work without extreme slowdown then... 
	-I will look into Spatial OS, a platform made to be used for running large scale games. The issue here is that there might be costs involved or 'verifications'. 
	-If Spatial OS doesn't work, then I will use a C# profiler to truly see what is failing on the VM. 
	-I also can pottentially look into "TCP" and see if that is a solution.

-If above is done, figure out how to save the data of the clients that log onto the server.

## Anything Blocking?

Just figuring out how to find something strong enough to host this game. 

## Notes
-After I figure out how to save the data for the clients logging in then the game is done. The rest is whatever people want to make the game 'into', no more gross multiplayer topics besides sync-ing any new abilities given to characters as more characters are added into this "MMO".