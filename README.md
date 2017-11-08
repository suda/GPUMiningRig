# 6 GPU Mining Rig

## Parts, materials and tools

### Metal
* 5x 2020 50mm profiles
* 8x 2020 30mm profiles
* 2x 2020 15mm profiles
* 16x M3 10mm screws
* 36x M4 10mm screws
* 8x PC case 4mm screws
* 36x M4 nuts
* 24x M5 5mm screws
* Zip ties

### 3D Printed

* 6x [GPU Bracket Rail](parts/GPUBracketRail.stl)
* 6x [Raiser Rail](parts/RaiserRail.stl)
* [PSU Frame Left](parts/PSUFrameLeft.stl)
* [PSU Frame Right](parts/PSUFrameRight.stl)
* 2x [Right Angle Bracket](parts_others/90_bracket.stl)
* 8x [2020 Corner Connector](parts_others/2020_connect_v2.stl)
* 34x [T Slot nut](parts_others/t_slot_nut_m4.stl)

### Tools

* Drill
* M5 screw tap
* 3D Printer

## Assembly

1. Tap all the profiles
1. Put M4 nuts into all printed T Slot nuts
1. Place the T Slot nuts in the following profiles:
	* 2x 6 nuts in 50mm
	* 7 nuts in 50mm
	* 3 nuts in 40mm
	* 4x 2 nuts in 30mm
1. Screw the frame together using the M5 screws, 30mm+50mm profiles and the 2020 Corner Connectors
1. Screw the PSU frames to both power supplies
1. Screw the PSUs to the main frame
1. Screw the raiser beam using the M5 screws, 15mm+50mm profiles and the two 2020 Corner Connectors
1. Screw the beam to the frame using Right Angle Brackets
1. Screw the Raiser Rails to the beam using M4 screws
1. Screw the raisers to the Raiser Rails with M3 screws
1. Screw the GPU Bracket Rails to the upper part of the frame
1. Screw the MOBO standoffs and screw the MOBO
1. Place all the GPUs and screw them to the GPU Bracket Rails
1. Connect all the wires and use zip ties to clean up the cables

I recommend using [ethOS]() to manage your rigs. The setup very easy and fast saving a ton of work when configuring / managing more GPUs.

## 3rd Party Copyrights
Components in `parts_others` directory have been designed by following people:
* [2020 Corner Connector](https://www.thingiverse.com/thing:1100779) by [woodywong](https://www.thingiverse.com/woodywong/about)
* [Right Angle Bracket](https://www.thingiverse.com/thing:1810199) by [DCGTek](https://www.thingiverse.com/dcgtek/about)
* [T Slot nut](https://www.thingiverse.com/thing:1573410) by [Tomasz Mankiewicz](https://www.thingiverse.com/tomaq/about)
