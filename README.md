# 3 Inch Quad

This is a quad copter for 3 inch propellers driven by a 15xx motor and a 4s ESC. The center line of the motors are on a 130mm circle.

The specific configuration as designed:
* 1506-3950kv motors
* 14.8V 4s 850mAh 75c battery
* integrated ESC and controller with 20mm x 20mm mount and not more than 39mm on a side.

### Workflow

To print a complete frame, print the body, top, flange, and covers. You can use the body by itself without the top and covers, but to assemble the top, follow these steps: (assuming you have printed everything)

1. Bolt the flange to the top. I have used 1/4" #4 wood screws. You can also use M2 screws and nuts, or whatever hardware you have on hand. 
2. Using medium CA glue, glue the flange to the body being careful to align it correctly. DO NOT USE KICKER, because it leaves a residue on the plastic. Put a weight on it to hold it in place. 
3. Glue the covers over the motor wells.
4. Disassemble the top from the body and install the electricals.

#### Generating the models

The models are generated using FreeCAD v0.19. You can learn more about it here: https://www.freecadweb.org/ This is not a tutorial on how to use FreeCAD. I may put that in this readme at a later date.

The top, flange, and covers are stand-alone drawings. They are imported into freecad as 2D DXF drawings and then "extruded" to make the 3D models. 

The body is a merge of three drawings, the base, motors, and ducts. Each of these is imported into freecad (and extruded, etc) separately and then copy/pasted into the body to make the complete body.

To modify any of these drawings, what I do is make my modifications in the DXF first (I use QCAD for that) and then regenerate the models in freecad. 