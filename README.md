# W65C02Computer

### Description:
This is an 8 bit computer made with the W65C02 processor inspired by Ben Eater.
After board arrival, I will test the clk maximum speed (20MHz), some methods to write into ROM (take\`s too much time to write to it) and some other experiments with this design, beeing made mostly after the Ben Eater\`s original design.

### Features:
 - 8 bit processor
 - 1-10MHz CLK
 - 16K RAM
 - 32K ROM
 - USB C Powered
 - Serial interface
 - Multiple GPIO

<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/W65C02Computer/blob/main/ComputerPics/6502P3.png"/></td>
    <td><img src="https://github.com/Tonikiller10000/W65C02Computer/blob/main/ComputerPics/6502P1.png"/></td>
  </tr>
 </table>

Schematic:  
<img src="https://github.com/Tonikiller10000/W65C02Computer/blob/main/ComputerPics/6502P2.png"/>

Datasheets:
- W65C02 (Processor): https://eater.net/datasheets/w65c02s.pdf
- W65C22 (VIA): https://eater.net/datasheets/w65c22.pdf
- AT28C256 (32K x 8 EERPOM): https://ww1.microchip.com/downloads/en/DeviceDoc/doc0006.pdf
- CY7c199  (32K x 8  RAM): https://media.digikey.com/pdf/Data%20Sheets/Cypress%20PDFs/CY7C199.pdf
- R6551 (ACIA): https://pdf.datasheetcatalog.com/datasheets/2300/501026_DS.pdf
- MAX232 (Serial Port Driver): https://www.ti.com/lit/ds/symlink/max232.pdf?ts=1708783670366&ref_url=https%253A%252F%252Fwww.google.com%252F
- 74HC00 (NAND Gate): https://www.diodes.com/assets/Datasheets/74HC00.pdf



