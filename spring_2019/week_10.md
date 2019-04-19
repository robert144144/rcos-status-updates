
## Last Week's Accomplishments

IF YOU QUIT THE GAME WITHOUT PRESSING [ESC+Q] -> Then your data is not saved and you will respawn at spawn as a new character. 

Pressing [ESC+Q] will quit you from the game and save your position and potentially save other data once implemented (Such as inventory items).

It still does not load the data properly. I can write the Vector3 for example: (34, 56, 10) going to the file. Then I want to start clients at those coordinates the next time they log on.

## This Week's Plan

Load the coordinate data into the game properly for each client. 

[Potentially, week after next week... ]
-> Prevent [ESC+Q] logout during 'combat'.
-> Combat cannot occur in 'no-PvP' areas.

-> ONE FILE WHEN CLIENT CONNECTS TO THE SERVER -- consists of Usernames and Passwords
-> The Second file has [Username]-> [Data]. Data needs to be saved on the same line as the username or below the username. [Find username through readfile, then write file at that location.]

## Anything Blocking?
There is a Timeout issue. For some reason, Client and Server do not communicate for a certain number of time units that cause this issue. This timeout is based on the network connection strength someone else may have.

## Notes
Technically, these mechanics are not implemented, they have just been 'proven' to be implementable. The data saved is not 'important' data. This just shows that I can write to file from Server to Client.