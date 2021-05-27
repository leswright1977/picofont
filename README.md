# picofont
Fonts for the Raspberry Pico Display

**What is it?**

This is a new Font for the Raspberry Pi Pico Display from Pimoroni: https://shop.pimoroni.com/products/pico-display-pack

In src, is an easy to use pure Python implementation of a 5x7 ASCII font and associated helper functions.
bin-2-hex.xlsm is a handy spreadsheet I made for designing Characters, check it out!

This program and associated information is Open Source (see Licence), but if you have gotten value from these kinds of projects and think they are worth something, please consider donating, even a dollar: https://paypal.me/leslaboratory?locale.x=en_GB

The built in font (compiled into the firmware) is not particularly pretty:
![Screenshot](media/orig.png)

I wanted something a little more readable and pleasing to the eye for an upcoming project.
The code is a pure Python implementation, using a look up table for the chracter data, just like the good ol' days of assembly programming!

![Screenshot](media/pico.png)

Above:An image of the size 1 font

![Screenshot](media/mini.png)

Above:An image of the size 2 font
