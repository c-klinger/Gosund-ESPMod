# Gosund-ESPMod
The ESP12F branch is a small tweak from the original ESP-M2 adapter work to fit ESP-12F modules instead. Most of what comes after is from the original branch.

Adapter PCB to replace the CUCO-Z0 Modules on newer Gosund Smart Plugs with ESP-12F Modules. Enables to use custom firmware like [Tasmota](https://tasmota.github.io/docs/) again.

![PCB Picture](https://github.com/nutsoh/Gosund-ESPMod/blob/9bdc381ff534afd5aa08f2cfda641b2d8495a1db/images/pcb_assembled.jpg)

[Schematics](https://github.com/nutsoh/Gosund-ESPMod/blob/9bdc381ff534afd5aa08f2cfda641b2d8495a1db/gosund-esp-adapter.pdf)

The PCB features a Solder Jumper on the back side to control the pin mapping. 

## Tested Devices

### Gosund SP112, SP112_MAIN_AI_V1.0.
![SP112_MAIN_AI_V1.0](https://raw.githubusercontent.com/c-klinger/Gosund-ESPMod/main/images/SP112_MAIN_AI_V1-0.jpg)

**PCB:** IO16 and JP1 have to be shorted.

**Tasmota Template:** ``{"NAME":"Gosund SP112 ESP-M2","GPIO":[288,0,289,0,2656,2720,0,0,2624,257,224,0,32,0],"FLAG":0,"BASE":18}``

## PCB Specification
- Dimension: 20.3 mm * 18.7 mm
- PCB Thickness: 0.8mm

## Bill of Material

| Pos | References | Description | Value | Size | Quantity | Order Links \* | Notes |
|-----|------------|-------------|-------|------|----------|-------------|-------|
| 01 | U1 | ESP8285:ESP-M2 |  | ESP-M2 | 1 | [Aliexpress](https://s.click.aliexpress.com/e/_DFF7SI1) | |
| 02 | C1 | Capacitor | 100nF | 0805 | 1 | [Aliexpress](https://s.click.aliexpress.com/e/_DCEFDlb) | |
| 03 | R1, R2, R3, R4 | Resistor | 10k | 0805 | 4 | [Aliexpress](https://s.click.aliexpress.com/e/_DFfLtiN)  | 

\* *I have not tested all parts using this order links, no guarantee that every linked component works. Aliexpress links are affiliate links, so i will get a small commission when you order using this link. This will help me with further projects. Thanks.*


## LICENSE
[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

All content in this repository is is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-nc-sa/4.0/).

