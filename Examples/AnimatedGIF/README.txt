This is an example of creating an
animated surface rotation GIF file
using pyeq3 and matplotlib.
see http://commonproblems.readthedocs.io/en/latest/


Step 1: Install matplotlib, imagemagick and gifsicle

On Debian or Ubuntu Linux, you can use this command:

sudo apt-get install imagemagick python3-matplotlib gifsicle python3-pil

and then install pyeq3 with the command:

pip install pyeq3



Step 2: Run the AnimatedGIF example

From a command prompt run this command:

python3 AnimatedGIF.py

The example will display its progress
as it runs, and will create a file named
rotation.gif.



Step 3: View the animation

You can open the rotation.gif file in a
browser to see the animation.  The animation
may appear to stutter or jerk until fully loaded
from the computer's hard disk drive into the browser.
