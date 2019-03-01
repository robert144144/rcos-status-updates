## Last Week's Accomplishments

-VM bugs: It is NOT the networking. The game seems to have 'not responding' because of not having the Blender and Maya models correctly.
-OK, the bug is the fact that the VM was created with low vCPU and GB's.

NEW VM:
-> 16 vCPUs, 80 GB memory... Apparently max GPU's is 2; this is where optimizations matter... 
-> Cutting O(n log n) things to O(n) things will actually save money... [Using 100$ Google Cloud Free Credit for these next 80 days free]
	-The VM is only on for like 30 minutes at a time so it does not cost much, but I'm fairly sure that it would cost more than 10 dollars if left on for a day.
	
-"d.exe -batchmode" Ran the program headless; now how to click the button in game from the weird black terminal thing.

## This Week's Plan

-Continue trying to start the server... with more complex graphics
-If above is done, figure out how to save the data of the clients that log onto the server.

## Anything Blocking?

My Server does not like rendering video.
-I keep guessing on ways to start the server and they all fail. 
-This VM has no GPU and so it can't run much more than a couple falling spheres.
May have to think about splitting stuff into multiple cores...

## Notes
