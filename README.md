# diy-accordion-tuner
## Introduction
Plans how to build an electronic accordion tuner device (including air pump).

I'm hoping to gather some ideas of how to build an electronic device that would help the 
process of tuning of accordions. The goal is to write instructions, build plans and open source software
to make it possible for a handy person to build the device and tune an accordion without any professional help. 

## Accordion tuning in general
Tuning accordions is more difficult in comparison to tuning instruments like piano or guitarrs.
For those instruments the strings are wrapped around tuning pins. It is just a matter of turning
such a pin to adjust the tension of its string.

For accordions on the other hand you first need to disassemble the accordion box to be able to access the
metal reeds. To tune a metal reed, you can change the elasticity or the weight of the reed. The elasticity can
be changed by scratching the reed plate.

To complicate it even more, the pitch that a metal reed is producing outside the box can differ slightly from the pitch
it produces inside the accordion box.

## Build components

A sketch:

* Raspberry Pi 3 Model B+ (https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/)
* Electronic air pump
* Microphone
* Soundcard

## Software

Sketchy plans:
Maybe a modified version of Entropy-Piano-Tuner 
https://github.com/levush/Entropy-Piano-Tuner

could be used as a starting point.
