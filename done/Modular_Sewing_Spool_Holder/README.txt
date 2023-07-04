                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


https://www.thingiverse.com/thing:2630378
Modular Sewing Spool Holder by xyzaxis is licensed under the Creative Commons - Attribution - Non-Commercial license.
http://creativecommons.org/licenses/by-nc/3.0/

# Summary

### Intro
This is a modular sewing spool holder system that uses tileable snap-together bases and snap-in pegs.

The snap-in peg design provides some neat advantages:
* Stronger pegs (the printed peg can be oriented along the X-Y axis)
* Choice of peg length
* Ability to replace broken pegs

The bases also snap together and can be tiled - the 4x4 and 5x5 grids have the same outside dimensions, so you can mix and match in a grid (see pics). I am working on additional bases for larger spools but they are not yet perfected.

### Printing this Thing - TL;DR

Optionally print a small peg and base for calibration, choose and print the appropriate base for your sewing spool size, then choose your peg length and print the corresponding number of pegs.

### Printing this Thing - Details


### Calibration (Optional) 

* Print the shorter peg and the snap-in calibration base to make sure your printer is dialed in. The peg should snap into the base with a solid click, and be difficult (but not impossible) to remove.

### Choose and print the right base

* The 5x5 grid supports spools up to 19mm in diameter and requires 25 pegs.
* The 4x4 grid supports spools from 19 to 27mm in diameter and requires 16 pegs.

### Choose the right peg length and print the right number of pegs

* The 66.5mm pegs should be just long enough to hold a standard height spool and its bobbin. However, if you put this in a drawer, you'll find that every time you close the drawer with any force, your bobbins go flying off the top of the pegs.

* The 81.5mm pegs are designed with some extra length to hold bobbins in place when inside a sliding drawer.


### Misc notes


The pegs are wider at the base to better fit a spool, and taper slightly towards the top until the last few cm, where the diameter is small enough to hold a bobbin.

The tallest peg height was selected to just fit inside smaller IKEA LINNMON drawers (this is the type of drawer shown in the pictures).

DesignSpark mechanical source files are included if you want to make shorter pegs. Don't try to scale the pegs with your slicer as it will mess up the proportions of the snap-in part of the peg.

(Shameless plug alert) A great accessory for this Thing is the [Improved Sewing Bobbin Clip](https://www.thingiverse.com/thing:2630295) - clipped bobbins fit on top of the spools. You can see some of these in the pics.


# Print Settings

Printer: Monoprice Maker Select v2.1
Rafts: No
Supports: No
Resolution: 0.2mm
Infill: 30%

Notes: 
0.2mm is enough resolution for the pegs to function properly. 

I found 30% infill was plenty for the base and pegs. 

I'd recommend printing the pegs with at least 3 shells, which shouldn't leave you with much infill.

Try not to use a brim with the pegs if possible. Cleaning the brim off of the snap-in parts of the pegs can be tricky.


# Post-Printing

Push the pegs firmly into the base. They should give a good snap and be completely solid (no wiggling).

If using more than one base, you can click the bases together by laying one male/female side on top of the matching female/male side and pushing down gently.



# How I Designed This

I really liked the basic concept of the [Spool holder for sewing thread](https://www.thingiverse.com/thing:1560220) - especially the multiple spool sizes in the same footprint - but it had a few shortcomings that I wanted to fix:

- The pegs were too short for my use (wanted longer pegs to hold sewing bobbins on top)
- The pegs were oriented along the Z axis, making them prone to breakage and challenging to print cleanly
- The bases had alignment pegs but didn't actually snap together

Using the source spool holder's STL file as a dimensional template, I built a new design from scratch in DesignSpark Mechanical. 

I fixed the peg length and strength problems by designing a snap-in peg system. It took a few iterations to get the snap-in peg tolerances just right, but printing the pegs separately fixed the strength problems (since I could lay the pegs flat on the plate) and the length problems (since I could print any peg length I wanted).

To solve the snap-together base problem, I took inspiration from interlocking track pieces from wooden trains. It looks a little funny, but it's just tight enough to stay put, and has the advantage of snapping together in any orientation.