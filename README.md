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
- Ensure you can see the new "ATmega328 on a breadboard (8 MHz internal clock)" board in your list of boards in the Tools > Board menu.

Where I got my Bootloader shield (but generally available)  
https://www.aliexpress.com/item/AVR-ISP-Shield-Burning-Bootloader-Programmer-Atmega328P-Bootloader-module-with-buzzer-and-LED-indicator-for-Arduino/32853007180.html

