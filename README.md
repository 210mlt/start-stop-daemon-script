# start-stop-daemon-script
test1.sh is a normal script, looping for ever, updating the root window name (dwm "bar title") every second.
test2.sh controlls it as a daemon, using start-stop-daemon

start-stop-daemon requires privilege 
The runing privilege can be adjusted tho. Edit user.txt

New crreate damon script:
used command: ./createdaemon.sh test1.sh "xdaemon"
edited afterwaardss:
xdaemon.rc:  added command argument 
xdaemon.src: changed user:group
