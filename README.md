# Z_EndStop_Voron2.4R2
Voron2.4r2 Z_EndStop STL

Space Provided on the Voron 2.4R2
After measuring the heights. the original Z_EndStop will never fit. its impossible.
- 20mm Linear Rail
- 7.42mm Thumb Nuts
- 27.4 Total
- Tolerance of 1mm Top and bottom
- Usable Space of = 25.4mm space for the Z_EndStop.

Dimensions of the Parts in Use:
- 16.04mm The pully pin cog.
- 11.17mm Circuit board is.
- 27.21mm Total
- Its impossible to fit the Z_EndStop without touching theHeatBed and or base plate. And the current design works by pushing the lower base plate cover sheet down.

The original z_EndstopStop that listed on the VORON Git is too large and protudes above and bellow the 20x20 linear rails.
there is also a Compressed/Narrow version out there but that is still too large!.
https://github.com/VoronDesign/Voron-Hardware/tree/master/Microswitch_Z_Endstop/STLs
As both these EndStops are too large and press into the base plate.
![](/images/before_touchBed.jpg) 

Objective:
- I have redrawn the Z_EndStop to cleanly fit between the 20x20 rail without touching the base. Some users like myself use a ACM or AliGloss aluminium coated panel that shorts the switch out if touched and if the Z_EndStop protudes past the linear rail it pushes down the sheet, asethetically does not look nice.

Solutions:
- Use the larger the existing hardware, lift the switch above the base plate and then raise the heat bed a few mm to accomodate the 27.21mm and loose some Z access.
OR
- Modify the EndStop to not use the GearPully cog as guide. being ABS and under a 100degree heat bed. issues are surely advised.

This STL is designed to fit perfectly, Due to the tolerances and spaces allowed I came up with this solution to remove the GearPully.

ONSHAPE CAD https://cad.onshape.com/documents/e1354a125be9dce09332e63b/w/70244db17e9ae51604cb706e/e/d2d49ef7c74e6b2f688bc911

Download in the STL folder

![](/images/render1.jpg) 
![](/images/render2.jpg) 

