##General preparation parts

###Overview
This section is a overview of most parts for certain operations used in particular equippment in the laboratory. The goal of this list is to provide analasys to help planing and designing a universal platform, with micro-controller NodeMCU, to use in a wide variety of equipment, from measuring instruments to self-regulating tools.

###Table of contents

- NodeMCU
- General equipment - basic parts
 * Display with rotary encoder
 * 3 state switch
 * Heat-bed
 * Ultrasonic bath
- Rotating equipment - basic parts
 * Stepper motor
 * DC motor
- Measuring equipment - basic parts
 * PH meter
 * Temperature meter
 * Fine Wwighing scale

###NodeMCU
![NodeMCU](http://www.seeedstudio.com/depot/images/113990105%201.jpg)
Source:http://www.seeedstudio.com/depot/images/113990105%201.jpg

The [NodeMCU](http://frightanic.com/iot/comparison-of-esp8266-nodemcu-development-boards/#v2) is a open-source development kit, it features 13 general purpose inputs/outputs (GPIO) each GPIO can be PWM and a built in ESP8266 Wifi module with a PCB antenna. It comes vith a lua-based unformal firmware, or you can develope it in the arduino IDE environment. Due to its flexibleness, small size and low cost it fits in with the project requirements and goals.

###General equipment - basic parts

####Display with rotary encoder
For the best user interaction, a display with a rotary encoder will be implemented in all lab equipment. It will give a favorable overview of speed and duration for each process.The display menu will be arranged in rows, making it a simple and fast solution for scrolling througout all the settings.

####3 state switch
Is used for switching betwen different modes of operation. Its uses differ from one application to another, from a manual full throttle, to an emergency stop. Its full functionality will be defined in the software.

####Heat-bed
A PCB Heat-bed, commonly used in 3D printing technology, is a great solution for the [Heating plate / slide warmer](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#heat-plate) or [Magnetic stirrer](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#Magnetic-stirrer). Its slow heating process makes it appropriate for apications where lower(under 100°C) and more stable temperatures are preffered. Another advantage of the heat bed is its heat distribution as seen from the [Thermal picture](http://blog.brixandersen.dk/wp-content/uploads/IR003957.jpg). Together with a integrated thermistor it forms a self-regulating system, with the ability to heat up to a certain temperature and maintain it. 

###Rotating equipment - basic parts
![Rotating equipment](https://cloud.githubusercontent.com/assets/17159617/14168954/5cd9aafc-f725-11e5-80ed-7af6616375b1.jpg)
Source:http://bmskgroup.com/product/mixers-rotators-tubes/

The folowing list contains all basic parts used by rotating instruments for their operation. The list does not cover design features, which are specific for different types of equipment. In principle, all rotating lab equipment works the same way and differ mainly in the rotation speed and axis. 

####Stepper motor
Will be used in low RPM (15-100 rpm) devices such as the [rotating wheel](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#rotation-wheel) and [laboratory shaker](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#shaker), in cases where slow and controlled revolutions are favored.

####DC motor
In certain cases, e.g. [vortex mixer](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#Vortex-mixer) or [centrifuge](https://github.com/symbiolab/bio-labware/blob/master/010_general_preparation.md#Centrifuge), speed around 15,000 rpm is necessary to generate enough force.  DC motors are a good solution for high speeds and low cost.

