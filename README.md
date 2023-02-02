<h1 align="center">Vacuum fluorescent clock</h1>
<h3 align="center">Vacuum fluorescent clock schematic and pcb. Drives with STM32F103 "BluePill". Driver code in progress.</h3>
<h4>Standart schematic for STM32F103 MCU. MCU pins connected to BJT's base with 4.7k resistors. VCC to heater and logic is 5V provided by external supply. I use the AP1117 LDO to make 
2.5 V heater voltage and VT1 for PWM the heater, drived from MCU. 3 button switches to provide user clock configuration, like setting timer or clock bright. Cathodes drived via npn BJT's.</h4>
<h2><img align="center" src = "https://github.com/AlexDolgopolov/VacuumIndicatorSchematic/blob/main/images/SCH1.png"</h2>
<h4>This scheme discribes anode drivers. I use +25 V Q=0.1..0.4 external voltage generator with simple schematic based on blocking genrator.<b>Schematic and PCB for this external generator will be added soon
</b></h4>
<h2><img align="center" src = "https://github.com/AlexDolgopolov/VacuumIndicatorSchematic/blob/main/images/SCH2.png"</h2>
<h4>Connection between two PCB's realized by wires. If you open a PCB file in KiCAD, you can check the connections. Actually, it really doesn't matter how you connecting the wires, in STM32 driver<b>Will
be added soon.</b> you can remap the pins. But, PWM pins should be connected to heater.</h4>
<h2><img align="center" src = "https://github.com/AlexDolgopolov/VacuumIndicatorSchematic/blob/main/images/PCB.png"</h2>
<h4>Thank you for watching this simple project. Work in progress now.</h4>
