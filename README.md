# Bipolar-EHV-Generator
An extreme high voltage generator that utilizes a bipolar setup to effectively create a 300kV+ voltage difference.

<img width="2160" height="1059" alt="Assembly_2026-Aug-29_12-14-39AM-000_CustomizedView10577367450" src="https://github.com/user-attachments/assets/d8f29226-4f89-4985-8d73-49f5cc972cbf" />

# How does it work?

The custom ZVS driver drives the self-wound HV AC transformer. That transformer is connected to both inputs of voltage mulitpliers.
By configuring each multiplier to output a +HV and the other to do a -HV, it is no longer a +HV - GND difference, but +HV -HV difference.

<img width="799" height="1007" alt="Screenshot 2026-08-28 at 5 43 17 PM" src="https://github.com/user-attachments/assets/92655b85-ee71-45d0-84ea-29727c41aeca" />

# PCB Pictures

<img width="1592" height="1063" alt="Screenshot 2026-08-28 at 5 44 21 PM" src="https://github.com/user-attachments/assets/33c6c5dd-eef2-4be2-91cd-a2984a5ab455" />
<img width="1437" height="313" alt="Screenshot 2026-08-28 at 5 44 59 PM" src="https://github.com/user-attachments/assets/6d0b8ac0-a7a4-4cbb-bb25-c20dab842a00" />

# Bill of Materials

| Item                               |    Price | Link                                                                                                         |
| ---------------------------------- | -------: | ------------------------------------------------------------------------------------------------------------ |
| White PLA                          |      $13 | [Amazon](https://www.amazon.com/SUNLU-Printer-Filament-1-75mm-Printers/dp/B0BD7K5SQK/)                       |
| Kapton Tape                        |      $10 | [Amazon](https://www.amazon.com/Hxtape-Temperature-Polyimide-Printing-Soldering/dp/B07D5RRXTS/)              |
| 32 AWG Magnet Wire                 |      $13 | [Amazon](https://www.amazon.com/BNTECHGO-AWG-Magnet-Wire-Transformers/dp/B07JBQQR38/)                        |
| Transformer Core                   |      $23 | [Amazon](https://www.amazon.com/5pairs-UY1658-Transformer-ferrite-Material/dp/B0146OG8VK/r)                  |
| 16 AWG                             |       $8 | [Amazon](https://www.amazon.com/Silicone-Electrical-Cable%EF%BC%8810ft-Temperature-Resistant/dp/B0D93K21TN/) |
| Momentary Push Button              |       $3 | [AliExpress](https://www.aliexpress.us/item/3256812230348809.html)                                           |
| 40 × 2CL77 Diodes                  |      $13 | [AliExpress](https://www.aliexpress.us/item/3256802425242911.html)                                           |
| 40 × 20 kV 1 nF Capacitors         |      $14 | [AliExpress](https://www.aliexpress.us/item/3256809649447491.html)                                           |
| 24 V 20 A SMPS                     |      $22 | [Amazon](https://www.amazon.com/HPMN-24V-15A-360W-Transformer/dp/B0DPKJPB5P)                                 |
| Mains Cable                        |       $4 | [AliExpress](https://www.aliexpress.us/item/3256802936747637.html)                                           |
| IRFP250 MOSFETs                    |       $6 | [AliExpress](https://www.aliexpress.us/item/3256806932452420.html)                                           |
| 470 Ω 2 W Resistors                |       $2 | [AliExpress](https://www.aliexpress.us/item/3256802900888178.html)                                           |
| 0.47 µH 10 A Inductor              |       $6 | [AliExpress](https://www.aliexpress.us/item/3256806537093956.html)                                           |
| 2-Pin Screw Terminals              |       $3 | [AliExpress](https://www.aliexpress.us/item/3256806674476213.html)                                           |
| 3-Pin Screw Terminals              |       $4 | [AliExpress](https://www.aliexpress.us/item/3256806674476213.html)                                           |
| 1N4742A 12 V Zener Diodes          |       $1 | [AliExpress](https://www.aliexpress.us/item/2255799836200735.html)                                           |
| UF4007 400 V Fast-Switching Diodes |       $2 | [AliExpress](https://www.aliexpress.us/item/2255800018624086.html)                                           |
| 0.68 µF Film Capacitors            |       $3 | [AliExpress](https://www.aliexpress.us/item/3256801916333851.html)                                           |
| 50 V 1000 µF Electrolytics         |       $5 | [AliExpress](https://www.aliexpress.us/item/3256811625053645.html)                                           |
| Multiplier PCB                     |       $8 | JLCPCB                                                                                                       |
| ZVS PCB                            |      $16 | JLCPCB                                                                                                       |
| JLC Shipping                       |      $15 | JLCPCB                                                                                                       |
| **Total**                          | **$194** |                                                                                                              |

