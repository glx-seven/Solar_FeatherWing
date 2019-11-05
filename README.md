# Solar_FeatherWing
##  Description
Run your projects with free sun-power :).

The ST SPV1040 takes care of the MPPT of your solar-panel.
An integrated TI INA219 power monitor IC (at I2C address 0x48) lets you observe your battery voltage and the charge/discharge rate.

The maximum voltage of the solar-cell is 5.5V. 
Never connect batteries on your feather board (or anywhere else) and this wing at the same time.

## BOM
| Part | Value | Package | Description |
| --- | --- | --- | --- |
| C1 | 22uF | C0603K | capacitor |
| C2 | 22uF | C0603K   | capacitor |
| C3 | 1nF | C0603K | capacitor |
| C4 | 1nF | C0603K | capacitor |
| C5 | 1uF | C0603K | capacitor |
| C6 | 22uF | C0603K | capacitor |
| C7 | 22uF | C0603K | capacitor |
| C8 | 22uF | C0603K | capacitor |
| C10 | 100nF | C0603K | capacitor |
| D1 | NSR0530HT1G | SOD323 | diode |
| D2 | SMBJ5339B-TP | SMB | z-diode for protection |
| IC1 | SPV1040T | TSSOP8 | Solar-charge IC |
| IC2 | INA219AIDCNR | SOT65P280X145-8N | power monitor |
| J1 | 1X2-3.5MM | 1X2-3.5MM | terminal header |
| L1 | 10uH | DR74 | inductor | Shielded Iinductor |
| MS1 | FEATHERWING | FEATHERWING | adafruit featherwing layout |
| R1 | 1k | R0603 | resistor |
| R2 | 50m | R0603 | resistor; current-limit of the charger |
| R3 | 1k | R0603 | resistor |
| R4 | 1k | R0603 | resistor |
| R5 | 1.2M | R0603 | resistor |
| R6 | 390k | R0603 | resistor |
| R7 | 100m | R1206 | resistor; shunt resistor for current-measurement |
| R8 | 4.7k | R0603 | resistor; i2c pullup |
| R9 | 4.7k | R0603 | resistor; i2c pullup |
