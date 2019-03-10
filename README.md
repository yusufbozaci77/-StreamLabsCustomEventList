# -StreamLabsCustomEventList
This is the code for a custom event list for stream labs for use with streaming software like OBS.

Once in StreamLabs on the events list screen scroll to the bottom and set 'Enable Custom HTML/CSS' to 'Enabled'
Click the 'Reset Code' button below the code box.
Paste the code from the CustomEventList.css file into the code box below that on the CSS tab.

From there you can use the options to choose your colors, font, font size, and screen orientation.
background color will set the box color.
text color will set the text color. 
flip x will make the events slide in from right to left
flip y will put the events list on the bottom of the screen.

Make sure max events is set to 6, I recommend about 22px - 24px font size (but ite really depends on the font you use)
The animation options won't do anything as that is hard coded. 

The list should show 5 events on screen at a time (the sixth is hidden off screen which allows the events to slide off screen without one disappearing)
