# M624 24V Power Supply · Power

Ward-Beck Systems M624, 1968|1. Wiki page: [M624 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M624.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 10 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 132 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 8 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 25 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [14 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1968 - M624 - P05 - 1-1.jpg](MANUALS/1968%20-%20M624%20-%20P05%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Output voltage** | 22, 24, volts dc nominal two separate outputs (independently fused) |
| **Oad Current** | ampere per output, outputs |
| **Ripple** | volt maximum. |
| **Power requirements** | 115 volts ac, maximum. Hz 125 VA |
| **Ambient temperature** | degrees Celsius. |
| **Dimensions** | wide (83 mm 3.4&quot; high 13.7&quot; decp mm 336 ttiit) |
| **Weight** | 6.5 Ib. (3 kg). |

## Circuit description

From [1979 - M624 - Power Supply.pdf](MANUALS/1979%20-%20M624%20-%20Power%20Supply.pdf) pages 6-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M62h power supply is designed primarily for use with the Ward-Beck 600 scrics equipment but maybe used for any application requiring 24 volts dc, such a5 the operation of relays and lamps, eIc. Two independently fused 24V, 1.5A dc outputs are provided selection of primary transformer winding taps permit 10% adjustment of the nominal dc output voltage. conservatively rated silicon diode bridge assembly and computer grade filter capacitor ensure optimum performance characteristics and lony lerm dependabi ity The primary ac and secondary dc fuses are conveniently located on the module front panel power ON/OFF switch and associated indicator Vamp are also mounted on the front panel AI connections are Made via the MF6 frame receptacles. The MF6 connectors are wired for the required ac and dc operating conditions of the M624 module. Modules may therefore be interchanged without affecting the operation of the system. The modest size of 3.4 13.7 inches allows five M624 power supplies to be accommodated in onc standard rack mounting (19W 3.Sh) MF6 equipment frame Perforations in the mounting frame and module assure adequate vertical ventilation by natural convection

**INSIALLAIION**

The M624 plugs directly into the MF6 mounting frame which may bc installed in standard EIA 19 inch equipment rack with the hardware supplied with the rack. The MF6 frame is furnished with full guide complement in order to accept maximum of five M624 power supplies or any combination of single Or multiple width modules no[ exceeding 10 single width modules. If the mounting frame has been procured Icss receptacles, these may first be installed in the appropriate module positions. Note that the receptacle containing the ac Line voltage connections is inverted to provide thc mechanical polarizing necessary 40 prevent inadvertent insertion of other companion modules which do not operate Trom the ac Line Jumper terminals P2, 12 (chassis ground) of all power supplies on common frame together and connect #18 AWG wire from each frame of power supplies to the systems ground bus. If the M624 supply is used in WBS console system the following polarity and ground procedures apply: +24V: Fused side of all relay and Lamp circuits.

24V common: Normally connected to ground_ When used in console systems, it is normal practice Lo connect the +24V to the common side of all lamps, relays, etc, The control sidc of component is then switched to ground via an appropriate control switch or contact. Because the M62h is intended for general purpose Jamp illumination relay operation or other non-critical applications, the actual output voltage may vary in accordance with the Line input, and the output Load Thus the 24V specified is nominal dc output. In general, the 24V dc wili be within 207 for ali conditions, but when applications arise utilizing relays that do not Pull In below 18V the M624 should nol be used Use fuses with the correct ratings for primary and secondary functions. Failure to comply in this regard may cause permanent damage to the power supply

PARTS LiST

**MFG PART NUMBER**

Capacitor 4100 uF/75 Corner!

**FAH 4100-75-B2**

Bridge Rectifier

**PB60**

Indicator Lamp Eldema cFoz-RTS-1762

**FI F2 F3**

Fuse 2A S.B 2A F.B 2A F. B.

Buss

**MDL AGC**

Resistor 470 3w Dale

**CW-2B 470**

Switch

9201

Transformer Hammond

**WBS 80-9**

PoWER SuPPLY MOUNTING IRAY IISVAC 60 Hz.

**2ASB**

l80 16 50 IS0 140 50 130 L0 120 30 M10 20 to 0 0 90 90 10 IOO 2 0 10 30 40 5C

Ti BN 80-9 GN R 1 BK GU

+24v (F2) PFRUo

**2 A F3**

5, 6 +24v (F3) Ri}470 3w +24 v 7,8 ChAssIS 12 ci 41oOuF 75v

common

ConNECTORS REAR VIEW 13,14 coMMON 15,16 NOTES ShowN CONNECTED FOR 24v OPERATiON 2 FOR 22v OPERATION CONNECT PI-6 AND 5 3.FCR 26 V OPERATION CONNECT PI-6 AND 3

**APP SCALE**

624 -02 -001

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1TiNzOJtwJRqjLzJ75frZgRRZhgPcaUb7/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1TiNzOJtwJRqjLzJ75frZgRRZhgPcaUb7" width="240" alt="1968 - M624 - DOC - FRAME WIRING VIEWED FROM REAR.png"></a><br><sub>1968|1 · DOC - FRAME WIRING VIEWED FROM REAR · <a href="SCHEMATICS/1968%20-%20M624%20-%20DOC%20-%20FRAME%20WIRING%20VIEWED%20FROM%20REAR%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb0p0dXdFS0JVT0E/view?resourcekey=0-Ia5WrOLE5k59W5WnPJqQpw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb0p0dXdFS0JVT0E&resourcekey=0-Ia5WrOLE5k59W5WnPJqQpw" width="240" alt="1968 - M624 - OPERATION CONNECT PI.jpg"></a><br><sub>1968|1 · OPERATION CONNECT PI</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU29fa0EyTGhMYWM/view?resourcekey=0-aD1oCssyMqtqW5PAkvPKmQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU29fa0EyTGhMYWM&resourcekey=0-aD1oCssyMqtqW5PAkvPKmQ" width="240" alt="1968 - M624 - P01 - Cover.jpg"></a><br><sub>1968|1 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOEhUaE92WU9hSm8/view?resourcekey=0-WxJL1k6MZfXegTBsjaqtVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOEhUaE92WU9hSm8&resourcekey=0-WxJL1k6MZfXegTBsjaqtVw" width="240" alt="1968 - M624 - P02.jpg"></a><br><sub>1968|1 · P02</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkhtNm0wNlVZVFk/view?resourcekey=0-dXT_rZgXGqM2puZWuV56aA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkhtNm0wNlVZVFk&resourcekey=0-dXT_rZgXGqM2puZWuV56aA" width="240" alt="1968 - M624 - P04- Warranty.jpg"></a><br><sub>1968|1 · P04- Warranty</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTzk4cXJnUDFaY28/view?resourcekey=0-tYidl7IO_bjJI-7QVanuYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTzk4cXJnUDFaY28&resourcekey=0-tYidl7IO_bjJI-7QVanuYA" width="240" alt="1968 - M624 - P05 - 1-1.jpg"></a><br><sub>1968|1 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2VHcmhhNVlkdVk/view?resourcekey=0-1ojhxcY53PVwYecg2tQLqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2VHcmhhNVlkdVk&resourcekey=0-1ojhxcY53PVwYecg2tQLqw" width="240" alt="1968 - M624 - P06 - 2-1.jpg"></a><br><sub>1968|1 · P06 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaTlXWXF2THpUa2c/view?resourcekey=0-qCegNL_-SVLcvcPrwSxW5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaTlXWXF2THpUa2c&resourcekey=0-qCegNL_-SVLcvcPrwSxW5Q" width="240" alt="1968 - M624 - P07 - 3-1.jpg"></a><br><sub>1968|1 · P07 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdF96SUFwTld0aEE/view?resourcekey=0-DmVVFIebyto6dk8xyHxY8A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdF96SUFwTld0aEE&resourcekey=0-DmVVFIebyto6dk8xyHxY8A" width="240" alt="1968 - M624 - P08 - 4-1.jpg"></a><br><sub>1968|1 · P08 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU3pWSHhFRlZMcnc/view?resourcekey=0-vEX3VlGLDUqu2485cFlTUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU3pWSHhFRlZMcnc&resourcekey=0-vEX3VlGLDUqu2485cFlTUw" width="240" alt="1968 - M624 - Power Supply (2).pdf"></a><br><sub>1968|1 · Power Supply (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKck12MWV5eDMxQTQ/view?resourcekey=0-o5BCWABnL8enGJCcNAhCsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKck12MWV5eDMxQTQ&resourcekey=0-o5BCWABnL8enGJCcNAhCsQ" width="240" alt="1968 - M624 - Power Supply.pdf"></a><br><sub>1968|1 · Power Supply</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWFuRWZ5VmozbFE/view?resourcekey=0-QOJljhCfdSrTfus_IWPp6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWFuRWZ5VmozbFE&resourcekey=0-QOJljhCfdSrTfus_IWPp6A" width="240" alt="1968 - M624 - WBS test procedures 0.jpeg"></a><br><sub>1968|1 · WBS test procedures 0</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNF9hSEFsU19lN2s/view?resourcekey=0-GbXinRM7zzrImjNlx-tK0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNF9hSEFsU19lN2s&resourcekey=0-GbXinRM7zzrImjNlx-tK0Q" width="240" alt="1968 - M624 - WBS test procedures 1.jpeg"></a><br><sub>1968|1 · WBS test procedures 1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNnlHRlZkM3JsTm8/view?resourcekey=0-revQ6vu3rMBcMR5nVFaNdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNnlHRlZkM3JsTm8&resourcekey=0-revQ6vu3rMBcMR5nVFaNdw" width="240" alt="1977 - M624 - PRICE LIST - 7000 series - price list.jpg"></a><br><sub>1977|10 · PRICE LIST - 7000 series - price list</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXo5Qlg1WHhSVFU/view?resourcekey=0-w8rjcBS4MPo85YWFx8ocVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXo5Qlg1WHhSVFU&resourcekey=0-w8rjcBS4MPo85YWFx8ocVg" width="240" alt="1977 - M624 - PRICE LIST - price list.jpg"></a><br><sub>1977|10 · PRICE LIST - price list</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0Jtb2JMY0pLN2c/view?resourcekey=0-bK0Rj9J9DSJYmn3mkWQjXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0Jtb2JMY0pLN2c&resourcekey=0-bK0Rj9J9DSJYmn3mkWQjXQ" width="240" alt="1979 - M624 - P03 - TOC.jpg"></a><br><sub>1979|12 · P03 - TOC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRUxrRHNiMDhXNDQ/view?resourcekey=0-x8-1hqCjF1pnq0ni9YjxtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRUxrRHNiMDhXNDQ&resourcekey=0-x8-1hqCjF1pnq0ni9YjxtA" width="240" alt="1979 - M624 - Power Supply (2).pdf"></a><br><sub>1979|12 · Power Supply (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKejhQekhGdUF5ZE0/view?resourcekey=0-nsordg8pqcx5wII8F56GsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKejhQekhGdUF5ZE0&resourcekey=0-nsordg8pqcx5wII8F56GsQ" width="240" alt="1979 - M624 - Power Supply.pdf"></a><br><sub>1979|12 · Power Supply</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEwzdkNydVhib2M/view?resourcekey=0-hxZh85g48i2x-0bWlSuTXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEwzdkNydVhib2M&resourcekey=0-hxZh85g48i2x-0bWlSuTXQ" width="240" alt="19xx - M624 - AD - wbsps - ad - 600 series.jpg"></a><br><sub>19xx - M624 - AD - wbsps - ad - 600 series</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekxWelYzOThQRHM/view?resourcekey=0-rOJI88tOz3HG9m8bhg5NnQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekxWelYzOThQRHM&resourcekey=0-rOJI88tOz3HG9m8bhg5NnQ" width="240" alt="19xx - M624 - DOC - DSC03076 copy.jpg"></a><br><sub>19xx - M624 - DOC - DSC03076 copy</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkNNdlpPcmU0LWM/view?resourcekey=0-E_vjEZWmjI4zXD8QpocRHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkNNdlpPcmU0LWM&resourcekey=0-E_vjEZWmjI4zXD8QpocRHw" width="240" alt="19xx - M624 - DOC - L2042 - P05.jpg"></a><br><sub>19xx - M624 - DOC - L2042 - P05</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZWF1aGstemowUEU/view?resourcekey=0-WwNkILifjA9P_JxR7VEsoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZWF1aGstemowUEU&resourcekey=0-WwNkILifjA9P_JxR7VEsoA" width="240" alt="19xx - M624 - DOC - L2042 - P11.jpg"></a><br><sub>19xx - M624 - DOC - L2042 - P11</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUh0YVhIN2hjclE/view?resourcekey=0-5BbrKsqSG2dcdybh1CqyLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUh0YVhIN2hjclE&resourcekey=0-5BbrKsqSG2dcdybh1CqyLg" width="240" alt="19xx - M624 - DOC - L3242 - P05.jpg"></a><br><sub>19xx - M624 - DOC - L3242 - P05</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1ZUc05mNllNM1U/view?resourcekey=0-iG8RBRupfekSrUdybuCH8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1ZUc05mNllNM1U&resourcekey=0-iG8RBRupfekSrUdybuCH8g" width="240" alt="19xx - M624 - DOC - L3242 - P11.jpg"></a><br><sub>19xx - M624 - DOC - L3242 - P11</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M624 - DOC - wbsps - ad - 600 series](https://drive.google.com/file/d/0B0yR0b5T78SKYV84MnZPdmp4RXM/view?resourcekey=0-BYn5IKGKqKUqwhW73pe0eg)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1968 - 624-02-001 - POWER SUPPLY M624 SCHEMATIC - DRN C.S.O'CONNELL - ISS 1.kicad_sch](KICAD/1968%20-%20624-02-001%20-%20POWER%20SUPPLY%20M624%20SCHEMATIC%20-%20DRN%20C.S.O%27CONNELL%20-%20ISS%201.kicad_sch)
- [1968 - M624 - DOC - FRAME WIRING VIEWED FROM REAR.kicad_sch](KICAD/1968%20-%20M624%20-%20DOC%20-%20FRAME%20WIRING%20VIEWED%20FROM%20REAR.kicad_sch)
- [1979 - 624-02-001 - 24V POWER SUPPLY SCHEMATIC - DRN GEB - ENG GEB - ISS 2.kicad_sch](KICAD/1979%20-%20624-02-001%20-%2024V%20POWER%20SUPPLY%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20GEB%20-%20ISS%202.kicad_sch)
- [1979 - M624 - Power Supply (2) p3.kicad_sch](KICAD/1979%20-%20M624%20-%20Power%20Supply%20(2)%20p3.kicad_sch)
- [1979 - M624 - Power Supply (2) p9.kicad_sch](KICAD/1979%20-%20M624%20-%20Power%20Supply%20(2)%20p9.kicad_sch)
- [1979 - M624 - Power Supply p3.kicad_sch](KICAD/1979%20-%20M624%20-%20Power%20Supply%20p3.kicad_sch)
- [1979 - M624 - Power Supply p9.kicad_sch](KICAD/1979%20-%20M624%20-%20Power%20Supply%20p9.kicad_sch)
- [M624.kicad_sym](KICAD/M624.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
