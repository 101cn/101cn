# Cyclic

This project was to model individual parts, and using standard bolts, fasteners, washers and spacers to create an epicylic gear train, with a sun gear in the center with plantery gears around it, which are held in place by the main body

<img src="exploded-view-epicyclic-gear-train.png" alt="exploded view" width="48%" style="display:inline-block; margin-right:4%;">
<img src="epicyclic-gear-train.png" alt="assembled view" width="25%" style="display:inline-block;">

The main board that coats the whole gear train (in red) is fixed in place, whilst everything else is mated in position, therefore the structure can be used for simulation purposes. The gear trains can freely spin in place, and affect the other planetary gears

<table>
<tr>
<td><img src="close-up-standard-parts.png" alt="close-up standard parts" width="400"></td>
<td><img src="bearings.png" alt="bearings" width="320"></td>
</tr>
</table>

Looking closer, the standard bolts and washers can be seen, to fasten each planetary gear in place. The threads are designed for easier fits, whilst retaining enough tolerance for an easy assembly

Bearings are put into place to increase efficiency, via reduction of frictional force and also reducing wear and strain on each plantery gear

<table>
<tr>
<td><img src="anti-rotation-key.png" alt="anti-rotation key" width="250"><br><b>Anti-Rotation Key</b></td>
<td><img src="dowel-pin.png" alt="dowel pin" width="250"><br><b>Dowel Pin</b></td>
<td><img src="grub-screw.png" alt="grub screw" width="250"><br><b>Grub Screw</b></td>
</tr>
</table>

Anti rotation key setup shows 1 of 3 methods designed to initiate rotation from the spur gear to the shaft hub <br>
Grub screw relies on pure frictional force by driving the screw through the threads and making it contact with the shaft hub <br>
Dowel pin acts like a wedge between the shaft hub and the gear, causing the gear to sping with the shaft hub

<img src="shaft-hub-drawings.png" alt="mbd design of gear carrier" width="600">

I have also designed drawings for easier understanding about how each shaft hub is connected to the plantery gear. There sketch highlights interior parts that are hidden from view for easier understanding without obstructing clarity

<img src="gear-carrier.png" alt="mbd design of gear carrier" width="300">

Some of the parts designed were given MBD, which is a tolerance measurement for manufacturing purposes, for example the counterbore sink contains tolerance dimensions about depth and angle given before a tapped hole is introduced <br>
The drills used would all be standard, and manufactures would not need to get specialized drills, hence reducing the price of said product

<table>
<tr>
<td><img src="epicyclic-gear-train-drawing.png" alt="anti-rotation key" width="250"><br><b>Gear train drawing</b></td>
<td><img src="parts-table.png" alt="dowel pin" width="250"><br><b>Parts table</b></td>
<td><img src="exploded-drawing.png" alt="grub screw" width="250"><br><b>Exploded drawing</b></td>
</tr>
</table>

I also designed a drawing containing an assembled gear train and an exploded view of the gear train. The exploded view has its parts labelled with balloon tags, and a table is provided to show the amount of pieces necessary to build the whole gear train <br>
Often assembly can be difficult to follow from schematics, but the assembled drawing is cut in half to show the organisation of the fasteners, nuts and screws in place in order. The whole exploded view is exploded part by part in chronological order, so the idea is to just push it back together and it would simply arrange it self. This would help designers following my schematics find it easier to design and assemble this product
