A script designed to simplify starting and stopping servers in detatched screens.

1. Place a copy of this script in the directory you wish to run it from.
2. Open the script copy and edit the following variables at the top of the script:
	RUNUSER - The user the script should be run as. The script will not run if it is not run as this user. 
	SERVERNAME - A useful name to see the server listed as in screen. 
	RUNCOMMAND - The full command used to run the server.

The possible commands are:
start - starts the server in a new screen and checks to see if it is already running.
stop - tries to stop the server by issueing an interrupt to the detached screen.
restart - Attempts to restart the server in a new screen.
status - Tells you if the server is already running in a detatched screen.
update - WIP
MORE COMING SOON!

./server start
./server stop
./server restart
./server status
./server update
	
