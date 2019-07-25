# Solar_FeatherWing
##  Description
Run your projects with free sun-power :).


- The maximum voltage of the solar-cell is 5.5V. 
- As you maybe want to conserve power, there is a TPL5111 timer onboard. Its default wakeup-intervall are 30 sec, but can be modified by using SJ1. 
- SW1 activates the timer manually, there is also an exposed pad so you can connect e.g. an external switch.
- SW2 cuts the line to the EN-pin, if you don't want to use the timer (or e.g. if you want to re-program your device). 
- The default done-pin is D12, if you want to use another pin, cut SJ2 and use any pin you like via the exposed done-pad. 
- R7 and R8 are in parallel to program the timer-interval for the TPL5111. You can refer to the datasheet to select fitting values for your usecase. Alternatively you can use the trimmer when you activate it via SJ1.

## BOM
| Part | Value | Device | Package | Description |
| --- | --- | --- | --- | --- |
| C1 | 22uF | C-EUC0603K | C0603K | CAPACITOR |
| C2 | 22uF | C-EUC0603K | C0603K | CAPACITOR |
| C3 | 1nF | C-EUC0603K | C0603K | CAPACITOR |
| C4 | 1nF | C-EUC0603K | C0603K | CAPACITOR |
| C5 | 1uF | C-EUC0603K | C0603K | CAPACITOR |
| C6 | 22uF | C-EUC0603K | C0603K | CAPACITOR |
| C7 | 22uF | C-EUC0603K | C0603K | CAPACITOR|
| C8 | 22uF | C-EUC0603K | C0603K | CAPACITOR |
| C9 | 1uF | C-EUC0603K | C0603K | CAPACITOR |
| D1 | NSR0530HT1G | NSR0530HT1G | SOD323 | Schottky barrier diode |
| D2 | SMBJ5339B-TP | ZENER-DIODESMB | SMB | Z-Diode for overvoltage protection |
| IC1 | SPV1040T | SPV1040T | TSSOP8 | Solar-charger-IC |
| IC2 | TPL5111 | TPL5111 | SOT23-6 | Timer-IC |
| J1 | 1X2-3.5MM | 1X2-3.5MM | 1X2-3.5MM | 3.5mm Terminal block |
| L1 | 10uH | DR73 or DR74 | DR73 or DR74 | Shielded Inductor |
| R1 | 1k | R-EU_R0603 | R0603 | RESISTOR |
| R2 | 820m | R-EU_R0603 | R0603 | RESISTOR |
| R3 | 1k | R-EU_R0603 | R0603 | RESISTOR |
| R4 | 1k | R-EU_R0603 | R0603 | RESISTOR |
| R5 | 1.2M | R-EU_R0603 | R0603 | RESISTOR |
| R6 | 390k | R-EU_R0603 | R0603 | RESISTOR |
| R7 | 32.4k | R-EU_R0603 | R0603 | RESISTOR; timer programming |
| R8 | 34.8k | R-EU_R0603 | R0603 | RESISTOR; timer programming |
| R9 | 1.2M | R-EU_R0603 | R0603 | RESISTOR |
| SJ1 | JUMPER3-0603-NC | JUMPER3-0603-NC | JUMPER3-0603_NC | 3 Pin Solder-Jumpers |
| SJ2 | JUMPER2-0603-NC | JUMPER2-0603-NC | JUMPER2-0603_NC | 2 Pin Solder-Jumpers |
| SW1 | C&K KSS221GLFS | SWITCH_PUSHBUTTON | C&K_KSS BTN_CK_KSS | Buttons |
| SW2 | SW-K3-1290S-J1 | SW-K3-1290S-J1 | WE 450404015514 | Slide switch |
| TM1 | TRIMPOTTC33X | TC33X | SMT trimmer potentiometer part number TC33X |
