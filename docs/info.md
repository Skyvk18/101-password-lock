<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Explain how your project works

The 101 Password Lock uses three input switches and logic gates to check if the correct password is entered. The circuit uses two AND gates and two NOT gates to compare the inputs to the password 101. When the correct combination is entered, the green LED turns on, indicating that the system is unlocked. If any other combination is entered the red LED turns on, indicating that the system is locked.

## How to test

Explain how to use your project

To test the project, use the first three input switches (input 0,1,2). Set input 0 to ON, input 1 to OFF, and input 2 to ON. This combinatiom creates the password 101, which should turn on the green LED. Try changing any of the switches to verify that the green LED turns off and the red LED turns on for incorrect combinations. If the combination is 101 the green LED should be on but when any kthe combination such as 110 is entered the red LED should be on.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any

3 input switches (1 or 0 positions) for entering the password

1 green LED to indicate an unlocked state

1 red LED to indicate a locked state

Resistors for the LEDs

Wires and a breadboard for connecting the components

The logic gates are printed on the chip, so no external logic gates are required
