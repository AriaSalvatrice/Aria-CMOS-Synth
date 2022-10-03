4017 Breakout Board Rev1
------------------------

8-step counter.

[Based on the Logic Noise series](https://hackaday.com/2015/04/24/logic-noise-sequencing-in-silicon/). The article suggests using two 4017 to drive LEDs, but this design uses transistors instead. Seems to work fine. Layout built for a breadboard-style PCB. Harwired reset to limit it to 8 steps, which is more useful in conventional music than the chip's maximum of 10.

[FIXME] On the layout, R12, R13, and R14 are mislabeled, cross-reference with the schematic where I forgot to number them.

![Photo of the module](4017%20Photo.jpg)

------

_This repository documents my learning process. I advise against building those circuits or learning from them. See the [main README file](../README.md) for more information._