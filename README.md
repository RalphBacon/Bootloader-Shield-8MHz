# Bootloader Shield: run an Arduino @ 8MHz with no crystal

Easily upload a new bootloader with this shield, including the 8Mhz (no crystal) version

# See YouTube video #119 at https://www.youtube.com/ralphbacon  
(Direct Link to video: )

If you're into power saving with the Arduino chip, the ATMega328P, then running at 8Mhz without a crystal (or resonator) is a great step to getting the sleep power consumption down to under 20µA.

You can, of course, always use another Arduino as the intelligent device to upload a bootloader to a different Arduino using Dupont cables, but this bootloader shield makes it even easier: no wires, just plug it straight in to your Arduino and run the sketch.

If you want to use the 8Mhz Arduino on a breadboard bootloader then follow these simple instructions (take from Arduino.cc).  
(Full details: https://www.arduino.cc/en/Tutorial/ArduinoToBreadboard)

- Create a new folder in your Arduino sketches folder, called **hardware**. If you already have this, skip this step!
- Download the zipped folder called **breadboard-1-6-x.zip**, unzip it and place the folder in the new hardware folder.
- Restart your Arduino IDE 
- Ensure you can see the new "ATmega328 on a breadboard (8 MHz internal clock)" board in your list of boards in the Tools > Board menu (probably the last one in the list).

Where I got my Bootloader shield (but generally available)  
https://www.aliexpress.com/item/AVR-ISP-Shield-Burning-Bootloader-Programmer-Atmega328P-Bootloader-module-with-buzzer-and-LED-indicator-for-Arduino/32853007180.html

Once you have loaded this new bootloader onto your Arduino ATmega328P chip it will run from the internal 8Mhz oscillator, _even if you subsequently plug it into an Arduino board with a 16Mhz crystal present_. So don't get the µController chips mixed up!

Can you use this bootloader file for a surface mounted ATmega328P when burning a bootloader in the usual way of using a different Arduino as the ISP? Of course! It's just a description of what the chip is, defined by some special "fuse" bit settings (one of the ways to ensure you never can upload another sketch!).

Blank ATmega328P chips can be had for as little as £1.20 ($1.60) from the Far East (sometimes with a bootloader already loaded, which you can just overwrite).

If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so :)

My channel and blog are here:  
------------------------------------------------------------------  
https://www.youtube.com/RalphBacon  
https://ralphbacon.blog  
------------------------------------------------------------------  
