# MATRIX LED Project

## Description

FlipFlopLuminary is an innovative approach to LED matrix design, emphasizing the use of fundamental digital electronics components—specifically, flip-flops—to drive a 16x16 LED display. This project breaks down the barriers to entry for engaging with hardware programming, providing a hands-on experience that requires no advanced microcontroller knowledge. Explore various display modes that range from straightforward static displays to complex, dynamic patterns, all made possible through the clever use of basic IC technology.
- **The Stroll of the Apollo**: Utilizing the decade counter feature of the IC 4017, we can sequentially activate each LED from left to right.
  
- **Luminary Hypnosis**: The initial state of all LEDs is 0, so to create a shift effect, we will start by applying a static current to the 14-gate (Figure 6.a), which is the serial data-in gate of the IC. After each clk, it will transfer 1 into the IC, which by time will be from 0000 to 1000 to 1100 and so on. After reaching the state that is full of 1s, we need to find a way to turn off the static current, making 14-gate LOW.

- **Electron and Positron Interactions in Electromagnetic Fields**: Two points of light are established at the beginning and end of an LED matrix. These luminous points concurrently traverse the entire array, meeting each other at the center of the circuit. Upon this encounter, each point of light reverses its course, returning to its original position. This cycle of movement is then repeated, creating a dynamic and visually 

## Button Functions

The buttons on the MATRIX LED can perform the following functions:

- **Switch to Single RGB LED**: Allows you to focus on a single RGB LED.
- **Switch Between Modes**: Quickly toggle between available modes.
