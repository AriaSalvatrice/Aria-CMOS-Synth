# Aria Salvatrice's WIP CMOS Synth

This repository aims to document the Lunetta-style CMOS synth I'm building to learn more about electronics. 

This stuff is are currently provided publicly exclusively to solicit feedback. Depending on the quality of the completed synth and community interest, maybe I'll turn it into a proper open hardware project fit for human consumption one day. But for now, nobody should reproduce those builds, nor even attempt to learn something from them. I literally didn't know how to make a LED emit light rather than smoke at the start of 2022. I have no clue what I'm doing.

If you want to learn more about CMOS synths, your best introduction is [Elliot Williams' Logic Noise series](https://hackaday.com/series_of_posts/logic-noise/), then to dig deeper, the [Lunetta forums on electro-music.com](https://electro-music.com/forum/forum-160.html). 

I document my build [in a thread on the Look Mum No Computer forum](https://lookmumnocomputer.discourse.group/t/starting-a-little-cmos-synth-build/5375/), post the infrequent video [on my Youtube](https://www.youtube.com/c/AriaSalvatrice), and post [excessively detailed updates in between the gay shitposts on my personal Tweeter that nobody should follow](https://twitter.com/AriaSalvatrice). 


## Overall Design

All the guts of the synth are exposed as bare PCBs with male header pins, that the performer patches with female DuPont cables. 

The system runs on +12V DC. It currently would also work on +9V, but the values are tuned for +12V, so pitches and envelopes are different at +9V.

The modules tile to an approximate 60×60mm grid.


## Mechanical Design

The modules are currently printed with PLA. The models were made with FreeCAD. As I don't know FreeCAD well, they are not very well made and can require some post-processing in Blender, the main value of the FreeCAD project is to have a set of measurements that works pretty well. 


## Custom Protoboard

I made a little prototype board for this project that imitates a breadboard layout. Revision 1 has various mistakes, I will document it better when I do a revision 2. 

— Aria Salvatrice <mailto:woof@aria.dog>