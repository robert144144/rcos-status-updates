
## Last Week's Accomplishments

-Reading from the data file on the server sometimes works. This will allow the client to load at the position recorded in the data file. This also means other data besides position can be stored, such as rank.
-The Quit and Save Data feature seems to sometimes work. Not sure what causes it to work and not some other times.
-The write to file data saving will only occur along with the quit game button press
-If the game does not quit via button press, then the file does not get saved. [Alt+F4 quits without saving]

-The timeout issue was based on how many tabs and internet applications were running at a time for certain clients. 

## This Week's Plan

Figure out why the saving seems to only work sometimes but not all the time.

## Anything Blocking?
No...? Honestly not sure. Anytime I feel the code could be so fragmented that it all just breaks. Instead of actually solving problems, sometimes a 'work-around' solution is found to get to the minimal viable product without actually implementing a necessary feature. An example is how the data is only saved when clients quit the game, this is because I don't understand how to send a message "OnClientDisconnect"; only via "Input"

## Notes
