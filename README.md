# Gadget
A simple kernelmode WDF driver.

# Abstract
This project is a simple kernelmode WDF driver. Its intent is to be a purely learning platform.
I am making zero pretenses that this will change the world, but is soley for my edification.

# What does Gadget do?
Gadget will simulate a simple machine which has a single 32-bit register. This register
represents a color. Its format will be: `RRGGBBAA`, where each letter is a 4-bit value.
I will consider this project functionally complete when I can read/write this value, and
have a program to interface with the gadget.