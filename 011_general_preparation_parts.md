##General preparation parts

###Table of contents

- Description
- Rotating equipment basic parts
 * Stepper motor
 * DC motor
 * Display
 * Rotary encoder
 * 3 state switch

###Description
In principle, all rotating lab equipment works the same way and differ mainly in the rotation speed and axis. The goal is to create a universal platform operateting all rotating instruments used in the laboratory environment.

###Rotating equipment - basic parts
The folowing list contains all basic parts used by rotating instruments for their operation. The list does not cover design features, which are specific for different types of equipment.

####Stepper motor
Will be used in low RPM (15-100 rpm) devices such as the [rotating wheel]() and [lab shaker](), in cases where slow and controlled revolutions are favored.

####DC motor
In certain cases, e.g. [vortex mixer](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#Vortex-mixer) or [centrifuge](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#Centrifuge) great speed is crucial to generate enough force. DC motors are a good solution for high speeds and low cost.

####Display
For the best user interaction, a display will be inplemented in all lab equipment. It will give a favorable overview of speed and duration for each process.

####Rotary encoder
The display menu will be arranged in rows, making it a simple and fast solution for scrolling througout all the settings. 

####3 state switch
Is used for switching betwen different modes of operation. Its uses differ from one application to another, from a manual full throttle, to an emergency stop. Its full functionality will be defined in the software.
