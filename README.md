# RP2040 + 12x12 LED Microcomputer

[RP2040 + 12x12 Display (Theme).pdf](https://github.com/user-attachments/files/31155070/RP2040.%2B.12x12.Display.Theme.pdf)

A small, custom RP2040-based microcomputer designed as my first serious electronics project.

This project is primarily a learning exercise. Over the past few weeks, I've been teaching myself electrical engineering, PCB design, and schematic layout, and this board is the result of putting that knowledge into practice.

## About the Project

The original goal wasn't necessarily to design a perfect, production-ready board. I wanted to learn how to design a reasonably complete schematic and PCB from the ground up, while keeping the design organized enough that someone else could actually review it without having to decipher a nightmare of wiring.

A lot of the design is based on reference designs, Phil's Lab tutorials, datasheets, and recommendations I've received while learning. If you recognize something that looks suspiciously like a reference design, that's probably because it is.

I haven't manufactured the PCB yet, so whether the board actually works remains to be seen. I've sourced the components, though, and the parts currently cost roughly **$30 USD**.

## Intended Use

The eventual plan is to 3D-print an enclosure for the board and connect various controls and peripherals through the exposed GPIO headers.

The primary demonstration project will probably be a simple **Snake game** running on a 10×10 RGB LED matrix, but I'd also like the board to be useful as a general-purpose RP2040 microcontroller platform.

## Current Status

* [x] Learn enough electronics to become dangerous
* [x] Design the schematic
* [x] Select and source components
* [x] Create the PCB layout
* [ ] Manufacture the PCB
* [ ] Assemble the board
* [ ] Power it on without releasing the magic smoke
* [ ] Test the hardware
* [ ] Build a 3D-printed enclosure
* [ ] Get Snake running

## Feedback

This is my **first PCB/electronics project**, so criticism is very welcome.

If you spot a bad design decision, questionable component choice, layout mistake, missing protection, or something that is simply going to explode when I turn it on, I'd genuinely like to know. The goal of putting this project on GitHub is partly to get it reviewed and learn from the mistakes before I manufacture it.

And if you think the design isn't worth salvaging, that's fine too. I'm completely willing to scrap it and start over if that's what I need to learn.

## Disclaimer

This board has **not been manufactured or tested yet**. Everything beyond the schematic and PCB design is currently theoretical.

If it works on the first try, I will be just as surprised as you are.
