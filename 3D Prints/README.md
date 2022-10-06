3D Prints
---------
The system tiles pretty well, but can use a tiny bit of postprocessing help: a heat gun, 3D pen, and deburring tool can help obtain a better fit.

The feet of supports require M3 heat set inserts. A soldering iron is required to install them, only use an old tip you don't mind ruining.

Adding the rest of the files as I double-check the versions, dimensions, and make test prints.


### `Synth Support System.FCStd`

A messy and exploratory file, as I don't know FreeCAD much yet. Still, might be useful to make variations, try out changing dimensions in the spreadsheet and see if it works. Be ready to double-check dimensions and post-process models in Blender if you use it.

### `./stl/Holding Ring.stl`

Hold feet together. Takes countersunk M3×12mm screws.

### `./stl/Support - 60x40 perfboard - single support.stl`

[UNVERIFIED MODEL] Print two per 40×60 mm perfboard. In the default orientation, where it is printed on its side, it requires no supports. 

For a smoother surface finish, it can alternatively be printed upside-down with small painted-on supports at the edge of PCB holder, as follows:

![](images/60x40%20upside-down.png)

Secure boards with M2x12 screws and nuts. Note that two contiguous perfboards will almost touch, pads to their sides might be at risk of shorting if used. 
