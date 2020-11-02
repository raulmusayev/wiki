---
title: "Client Commands"
descripion: List of all client commands.
---

| Command	        | Description																																																																											  |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /quit (/q) 	    | This command speaks for itself, it quits the game. You can also use /q, as it the exact same command, just shorter. 																																															      |
| /save 	   	    | /save is most likely the most commonly used default command, and probably the most useful. When you type /save, your current position is saved to savedpositions.txt in your user files directory, from where you can use it in scripts.   																	      |
| /rs 	   	    	| /rs (Raw Save) is like /save, but it only saves your current position and facing angle in rawpositions.txt in your user files directory. No extra information is saved such as class and weapons.                                          																	      |
| /interior  	    | Partly as important as /save, this command simply displays your current interior in chat.																																				    																	      |
| /fpslimit  	    | This command sets the limit of FPS (Frames Per Second) for your game. The higher the limit the smoother your game is. Has no effect if frame limiter is turned off in graphic options. The limit can be set between 20 and 90. 		    																	      |
| /pagesize  	    | /pagesize is used to choose the amount of lines of chat to show. This can be anything from 10 to 20 lines. Pagesize is 10 by default.																																											      |
| /headmove  	    | This command will enable/disable the players head movements, however it is handled locally so other players will still see your head move.																																										  |
| /timestamp 	    | This command will show/hide a time next to all messages in the chatbox. The time that is displayed is your computer's time, not the server time.																																								      |
| /dl    	   	    |  DL stands for debug labels. This command toggles debug labels on vehicles, which show the vehicle ID, model, health, whether the vehicle is pre-loaded, distance from the player, trailer, available seats, current position and spawn position. 																  |
| /nametagstatus  	| This command was added in 0.3x. When enabled (which it is by default), players will see a small hourglass icon next to the nametag of paused players. This includes minimising (alt-tab), the pause menu (ESC), lost connection (crash/timeout) and when taking screenshots that freeze the game for over 3 seconds.|
| /mem 				| Shows the current amount of memory usage. (Although, it usually only prints 128 MB.)																																																								  |
| /audiomsg 		| Enables/Disables the message that prints when a url is streamed to a client. 																																																										  |
| /fontsize 	    | Changes the font size of the UI (chat, dialogs etc.). Valid fontsize is -3 to 5. 																																																									  |
| /ctd 				| This command was added in SA-MP 0.3.7 RC2. It enables client debugging of the player camera target. 																																																				  |
| /rcon 			| More related to the server rather than the client. This command is used to execute RCON commands. RCON is the built-in admin system. RCON stands for [Remote Control](../server/ControllingServer#using-rcon). 																												  |