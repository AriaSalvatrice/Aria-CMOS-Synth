Protoboard Rev2B
----------------

Inspired by commercialy available Permanent Prototype boards, and [Analog Output's Protoboard for Eurorack and Kosmo](https://github.com/holmesrichards/Protoboard). It's 99×99 mm, to get the best deal from PCB fab houses.

![3D view](Prototype%20Board%203D%20View.png)

There's built-in reverse voltage protection, a status LED, a main decoupling capacitor, room for 6 potentiometers or tactile buttons, and two half-breadboard layouts stacked over each other, with power rails.

The footprints at the bottom can be populated with pushbuttons or potentiometers. They are not connected to the rest of the circuit, but the topmost pad of each group can be used to run wires. Bear in mind that potentiometers are mounted with the pins in reverse order.

The 2 groups of 12 pins at the top and 2 groups of 4 pins on the sides are not connected to anything either. Use them creatively, for example for I/O.

The [W], [X], [Y] and [Z] rows are comprised of 6 groups of 5 pads each, which could be useful to run a signal below a chip.

Those boards are for a single rail power supply, limiting their usefulness for most synthesizer projects.

These are the files for Rev2B. Rev2A has been sent to fabricate (will update). Rev2B is the same with a minor correction (misaligned tracks) and has not been tested.

![Photo of the module](Protoboard%20Photo.jpg)

This is a picture of Rev1, which has a few flaws (such as the status LED shorting if populated). It was my first PCB ever, so I'm happy it even worked at all.

------

_This repository documents my learning process. I advise against building those circuits or learning from them. See the [main README file](../README.md) for more information._