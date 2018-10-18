---
title: Electronic Drink Dispenser
made: made in theta tau
weight: 6
icons:
- title: C++
  icon_name: devicon-cplusplus-plain
---
The Electronic Drink Dispenser uses a chest freezer, 12W battery, force sensor, flex sensor, water pump, motor, LED screen, and Arduino One to both mechanically and electronically dispense liquid from a 5 gallon jug. I programmed a switch in C++ using an Arduino One to send a current to the motor that powers the water pump depending on the bend-angle of a resistance-detecting flex sensor wired to a handle on the chest freezer. I also implemented a custom conversion equation from the force sensor's Newtons to liters to be displayed on the LED screen.
