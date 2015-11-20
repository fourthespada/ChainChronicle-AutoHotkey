Chain Chronicle!
========================

Autohotkey script to run the ring loop on chain chronicle (esp. while you're away from your computer!).

It will do 50x AC exchange, 50x challenge recruit, then attempt to sell everything in your sell screen until it hits the locked cards.  Script will repeat forever until paused or stopped.

Uses findclick in the ring shop & challenge recruit to avoid clicking dangerous things.

Uses a rescue function to break out of circumstances such as daily login bonus and prysma popups..etc.

Pushbullet notifications so you can get progress notifications while at work/school!

Safeguard to stop if you fall under 10k rings (gumi changes rate while you're away).  




Usage
=====

Install autohotkey

Download all files into any folder

Optional: Edit CC Rings Advanced.ahk global variables near the top

> To Enable pushbullet notifications, paste in your PB_Token AND set PBDebug to 1

Double click the script & watch your notifications pane for the green "H"

Place Bluestacks on top left corner of the monitor and start Chain Chronicle.

Make sure your sell screen is arranged by "Acquired".  Make sure to LOCK your CARDS since the script will automatically sell all the latest cards and then some.

MAKE SURE TO LOCK THE CARDS YOU DON'T WANT TO SELL.

F5 to start script
Pause key to pause
F12 to stop all scripts & reload

F10 for Findclick debugger
F11 to enable Mouse Position Tooltip if you need to modify script coordinates.



PS:
> Utilizing a 1920x1080 monitor with default bluestacks resolution
> Removed Findclick "r" option due to strange bug with occasional "Window Not Found".  Feel free to add it back.
> Thought of capturing screen / upload to imgur then send PB push but too lazy to do that now...