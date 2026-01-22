# OKLCH-Minecraft-Colour-Wheel
A Number of different colour wheels and gradients that display the average colours of Minecraft blocks, using the OKLHC colour space. Hover over a block to see its full name, and click to pin the name permanently. This was created for personal use, but I decided to share it in case others wanted to use it as well.

Usage: you will be required to upload the CSV and texture data. For the CSV, simply open in a program like Excel, select all (control-A on Windows) and copy (control-C); make sure you selected and copied all the data (including the top row). Then, paste the information into the text box. For the CSV file, simply upload the "textures.zip" file. Finally, click "process data" to show the colour wheels.
Block names will appear when you hover over the block icon, and will remain in place when clicked until clicked again. (The area to click is actually a circle centred on the centre of each block, so it doesn't exactly match the edges of the icon).

Details: This colour wheel uses OKLCH, a perception-based colour system. For more information on OKLCH, visit oklch.com. The first three wheels show hue along the angular axis and chroma (saturation) along the radial axis. The radial distance is not proportional to chroma, however, as each ring has been scaled for equal area and chroma levels are distributed to give a slight overrepresentation of medium chromas (where most Minecraft blocks lie). 
The colour wheels show lightnesses of 35%, 60%, and 85%, respectively, with each block plotted to the closest colour wheel. Very low chromas are omitted from the colour wheels, as are colours outside of a P3 gamut (the reason for the irregular shapes).
The colour field shows medium chroma blocks (2-15% chroma) from 10-100° hue (reds to yellows) along the x-axis and 20-80% lightness along the y-axis.
The gradients show colours below 4% chroma on cool, true neutral, and warm grey gradients, respectively (on whichever gradient the hue and chroma most closely match).

Some bugs remain to be ironed out, so please leave a comment if you run into any issues or have feedback.

Hope you enjoy!
