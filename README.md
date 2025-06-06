# Player

Ever Wanted to just play with a bunch on sensors with LEDs

## Schematic
![](https://github.com/titan00000001/Button/blob/main/Screenshot%20(18).png)

## PCB
![](https://github.com/titan00000001/Button/blob/main/Screenshot%20(17).png)
![](https://github.com/titan00000001/Button/blob/main/solder.png)

## Features
- 3 LEDs
- Light Based LED
- switch controlled LED
- Adjustable LED

## How to build
Just order the PCB & components, open up the KiCAD file and build it accordingly.

## BOM
"BT1","1","Battery_Cell","Battery:BatteryHolder_Keystone_3034_1x20mm","~"
"D1,D2,D3","3","LED","LED_THT:LED_D3.0mm","~"
"R1","1","R_US","Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal","~"
"R2","1","R_Photo","OptoDevice:R_LDR_5.1x4.3mm_P3.4mm_Vertical","~"
"R3","1","R_US","Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal","~"
"RV1","1","R_Potentiometer_Trim_US","Potentiometer_THT:Potentiometer_Vishay_T73YP_Vertical","~"
"SW1","1","SW_Push","Button_Switch_THT:SW_PUSH_6mm","~"

Made by `@vinay nor` on slack :D

Made as a part of http://solder.hackclub.com/!
