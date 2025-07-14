# Torque-Walker
![](https://github.com/DylM0nster22/Gryo-Walker/blob/main/Images/465948232-7f8f9d03-4806-4a0e-bb94-5671ee7b1b8f.jpg)

## Background

For our project for Undercity, we made a torque walker combat robot. This style of robot has two diagonally spinning blades, with one on each side of the robot. The blades rotate in opposite directions. By adjusting the speed of each blade, the torque reaction causes the robot to pivot, which can be used to create a walking motion. 

The blades and frame were all printed from PLA. The robot has two RS2205 motors, one per weapon, which are held on with M3 x 8mm screws. These motors are drived by LanRC 35A ESCs, which are in turn powered by a 300mah Gaoneng LiHV 3S battery. The robot is powered on and off thorugh a fingertech switch, with the switch located in the bottom of the robot. We used a Malenki HV as our receiver, as it is what we had on hand. All of the electronics are held in by the bottom plate, which was held on with 4 M3 plastites. 

## Features

* Two large 5" diameter asymmetric disk weapons
* Tip speed exceeding 300 mph
* 3S 300mah High Voltage LiPo
* Able to be built with only off the shelf parts and 3D prints.

## Images

![](https://github.com/DylM0nster22/Gryo-Walker/blob/main/Images/PXL_20250714_100501199.jpg)

![](https://github.com/DylM0nster22/Gryo-Walker/blob/main/Images/PXL_20250714_100454253.jpg)

![](https://github.com/DylM0nster22/Gryo-Walker/blob/main/Images/PXL_20250714_100508559.jpg)

## Build Process

### Printing

** IT IS VERY IMPORTANT THAT WHEN PRINTING THE WEAPONS, ONE OF THE WEAPONS NEEDS TO BE MIRRORED. **

To begin the build process, first print all of the parts out of PLA. The robot is compact enough to be underweight for the plastic antweight class with almost any print settings, but the recommended settings are at least 4 walls 15% infil for the frame and all top layers (solid) for the weapons. This ensures that the robot is capable of holding up to the forces of combat.

### Electrical

The first step in the electrical system is to take a male XT30 and solder a black wire onto the negative side, and a red wire to the positive side (matching the battey). Solder the negative wire onto the negative terminal of the Malenki, and the positive wire onto one of the switch's tabs. Then solder another red wire onto the other tab of the switch, and then the other side of the wire can then be soldered onto the Malenki's positive terminal. 

Next, solder white signal wires onto each of the Malenki's weapon channel signal pads. Each signal wire can then be soldered onto an ESC. To power the ESCs, daisychain off of the Malenki's power pads to one ESC, and then from that ESC to the next. 

Put the Malenki, switch, and ESCs inside the robot and have the motors outside the robot, with the phase wires running through their slots. The three phase wires from each motor can then be soldered onto each ESC's three phase wire pads. 

Make sure to wrap everything in electrical tape to prevent any shorts.

### Assembly

The first step in assembling the robot is supergluing the switch into a corner. Pay attention to roughly where in the corner the switch hole is located on the top plate. However, it does not matter which corner, as the top plate can be flipped to line up properly. Depending on how the switch lines up, you may need to expand the hole on the top plate. This can be done by twisting flush cutters on the hole.

The motors can now be attached using four M3 x 8mm screws on each motor. Be careful not to use screws that are too long, as they can damage the motor's windings and cause a short. 

The weapons are attached by pressing them onto the motor can and putting a nut on the end of the shaft to hold them on. Depending on how the weapon press fits onto the can, it may need to be reprinted with different horizontal expansion settings or adjusted with a soldering iron or dremel. Loctite should be used on the nut to ensure that the vibrations do not cause them to back off. 

At this point, the battery can be inserted into the robot, and the bottom plate can be screwed on with four M3 plastites. 

Your robot is now ready for combat!

## Bill of Materials

|Name                  |Quantity|Price |Link                                      |
|----------------------|--------|------|------------------------------------------|
|3S 300mah LiHV battery|1       |9.99  |https://share.google/nfxOtIxxwKT0yrfrc    |
|Malenki HV            |1       |46    |https://share.google/stp66j1LGnYxclgG8    |
|Fingertech Switch     |1       |7.99  |https://share.google/lWe0jieE8vX2Iteq6    |
|45A Drone ESC         |2       |39.6  |https://a.co/d/7bp3fm2                    |
|RS2205                |2       |14.62 |https://share.google/J0T66sHt1AGzdSqSs    |
|M3 x 8mm Screw        |8       |5.99  |https://a.co/d/7sxAajj                    |
|M3 Plastite           |4       |12.16 |https://www.mcmaster.com/product/96817A323|
|PLA Filament          |~250g   |5.99  |https://a.co/d/7vjEASh                    |
|XT30                  |1       |1.99  |https://share.google/1hgPaIf5fwCM2d9de    |
|Total:                |N/A     |144.33|N/A                                       |
