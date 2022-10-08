Percussions Module & Switching Sequencer Rev1
---------------------------------------------

3 circuits here, meant for my custom prototype board:
- Daisy-chainable XOR. Due to a mistake in the Rev 1 of my protoboard, not all the I/O is at the top, the 4th channel is on the side instead. 
- "Hi-Hat" Envelope with "Choke". Inspired by a circuit [from the Logic Noise series](https://hackaday.com/2015/04/10/logic-noise-more-cmos-cowbell/), just don't ask me how it works, I came up with it through experimentation.
- Gate to Trigger circuit based on Ken Stone's [CGS 24](https://sdiy.info/wiki/CGS_gate_to_trigger_converter). While I got it to work on breadboard, **I couldn't get my final build to work, and didn't manage to diagnose it yet**, so I don't know for sure whether my build or my layout is wrong. 
- Switching sequencer with oscillator, based on [Logic Noise](https://hackaday.com/2015/02/23/logic-noise-the-switching-sequencer/). Uses only 2 gate inputs and 4 pots, but the chip could support 3 and 8.

![Photo of the module](Percussions%20and%20Switching%20Sequencer%20Photo.jpg)

------

_This repository documents my learning process. I advise against building those circuits or learning from them. See the [main README file](../README.md) for more information._