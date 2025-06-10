# HMD-Fusion-DIY-Cases
A repo for storing my progress into developing a case/outift for the HMD Fusion phone. This repo includes schematic drawings, PCB drawings, and 3D models for the breakout board and testbench case. This repo will also include future dev kits for cases/outfits that make use of the exposed pins on the back of the HMD Fusion.

## TO DO
- Test pins for continuity and stability
- Develop a USB 2.0 circuit for expanding the I/O into a modular phone case

## I/O breakout board

![image](./Development/Breakout-Flex-PCB-Testing-Stand/Screenshot%202025-06-10%20121214.png "KiCAD V8 PCB drawing") 
KiCAD V8 PCB drawing

The breakout board is used to breakout the 6 pin header on the back of the phone and expand it into the ISO standard 2.54mm/0.1" 6 pin header for breadboard testing and development of external circuits. This board should be manufactured using a flexible PCB material, the case and basic funcationality of the spring pins were designed with this in mind. 

![image](./Development/Breakout-Flex-PCB-Testing-Stand/Screenshot%202025-06-10%20121229.png "KiCAD V8 3D Model Drawing")KiCAD V8 3D Model Drawing


## Testbench Case

There is a testbench case to go with this, it is best printed in TPU or other flexible materials to ensure the spring loaded pins on the breakout board do not get bent or damaged when removing the phone from the case. To insert the PCB into the case there are three edges that overlap the cutout of the PCB slot, this is a simple method used for the time being to get simple testing done but will be modified for an actual test run of a case/outfit. 

![image](./Development/Breakout%20Test%20Bench%20Case/HMD%20Fusion%20Tests%20v26.png "Testbench Case V1R1")Testbench Case V1R1
