<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a 0–255-minute countdown timer built entirely from Wokwi logic gates and flip-flops for Tiny Tapeout.

The eight DIP switches set the duration in binary. Reset loads that duration, and releasing reset starts the countdown. Changing switches while it runs has no effect.

The seven-segment display shows:
- Hours remaining, rounded up, during normal operation.
- Minutes remaining, rounded up, from the last 9 minutes.
- Seconds remaining, from the last 9 seconds.
The decimal point blinks once per second. At zero, the display flashes 0 and the dot continuously until reset. The design requires a 10 kHz clock.

## How to test

Set the amount of minutes using the switches in binary form.

## External hardware

7 Segment Display.
