<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Using a Mux, compare different 8-bit adder "ring oscillator" designs. Cout is fed into an inverter then into Cin. \
00 is a normal ring oscillator with 19 inverters (in recreation of COEN 451 lab).\
01 is a hybrid carry-lookahead adder (2x4bit), where we use the equation for C4 composed of Ps and Gs.\
10 is carry-ripple.\
11 is carry-select.

## How to test

Use digital pins to get output at digital pin. Multiply the frequency result by 1024 (10 clock dividers). 

## External hardware
Measuring equipment

