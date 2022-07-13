# magic-the-gathering-arena-bot
Magic The Gathering Arena bot that auto-plays to brute force daily and weekly rewards for gold/XP. Haven't used it since early 2020, likely doesn't work anymore! Uploading here for reference. 

MTGA must be in full screen mode, 1920 x 1080, on primary monitor, and graphics adjusted to low. MTGA client needs to
be already launched and signed into (or you can use a BAT file to launch this script and game simultaneously as a
scheduled task).

This bot will not work out of the box if you run it now. It's dependant on grayscale values at various points on
the screen. I'm not providing the values I used in the code, firstly because it's dependant on screen resolution and
untested on any machine other than my own, and second because I don't want just anybody who comes across this to be
able to take advantage and run a MTGA bot. I'm posting this primarily as a record of the code, not because I want to
distribute a bot. You will have to figure out the grayscale values in the Range class for yourself. I've left some
in for reference.

You can read more about it on my blog post below:

https://www.defaultroot.com/index.php/2020/07/07/a-magic-the-gathering-arena-bot-in-python/
