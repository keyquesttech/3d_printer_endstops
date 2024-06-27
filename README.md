
<div align="center">
  <strong><h1>3D Printer Endstops</h1></strong>
</div>

<div align="center">
  A collection of custom-made endstop/limit switches for 3D printers or CNC machines.
  These are drop-in replacements for the endstops in the Ratrig Vcore-3.1, however they may fit other printers.
</div>

<hr>

<div align="center">
  <table>
    <tr>
      <th>Endstop Durable</th>
      <th>Endstop Cherry</th>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/keyquesttech/3d_printer_endstops/main/Imgs/durable_endstop.png" alt="Endstop Durable" width="228" style="margin-top: 10px;"></td>
      <td><img src="https://raw.githubusercontent.com/keyquesttech/3d_printer_endstops/main/Imgs/cherry_endstop.png" alt="Endstop Cherry" width="200" style="margin-top: 10px;"></td>
    </tr>
  </table>
</div>

<div align="center">
  <strong><h1>Endstop Durable</h1></strong>
</div>

Inspired by the [RAT RIG ENDSTOP V1.1 - OMRON - NC](https://ratrig.com/catalog/product/view/id/1841/s/rat-rig-endstop-omron-nc/category/153/) this endstop includes all the features of the original:

- Made with an Omron [D2HW-A201D-AQ](https://github.com/keyquesttech/3d_printer_endstops/blob/main/Datasheets/Omron-Electronics-D2HW-A201D-AQ.pdf)
- Ideal for enclosed machines 
- Maximum Operating Temperature: +85°C  
- Minimum Operating Temperature: -40°C
- Wire fault protection. The endstop will trigger if any wire fails.
- 1,000,000 operations (clicks).

Plus some more:

- Ultra-bright magenta LED that lights up when pressed.
- Ultra-bright infrared LED specially integrated to facilitate viewing on webcams.

<div align="center">
  <strong><h1>Cherry Endstop</h1></strong>
</div>

A custom endstop for those looking to add some customization to their machine. This endstop uses standard 3-pin cherry or cherry style mechanical switches. The benefit of using this type of switches over a traditional limit switch are:

- Customization. You can use any style of switch you want as long as it's compatible with the PCB.
- Customize the actuation force and travel.
- Operation temperature depending on switch brand ranges from -40°C to +80°C.
- 100 million operations (clicks).
- Can add 3mm through-hole LED.

The downside of this design is that since cherry MX switches only have two terminals if ground fails the switch won't trigger, however an integrated LED will indicate any faults. This LED is separate from that of the trigger LED; the trigger LED is through-hole and goes in the switch.

<hr>

<div align="center">
  <strong><h1>Other projects from the autor (me)</h1></strong>
</div>

3D models / Prints:
 - [Mason jar ashtray](https://www.printables.com/model/918749-ashtray-mason-jar)
A mason jar attachment to make almost every jar in to an ashtray.

Printer mods:
 - [Servo nozzle brush (printables).](https://www.printables.com/model/913748-ratrig-vcore-331-servo-nozzle-brush)
A servo attached nozzle brush.
 - [Servo nozzle brush (github).](https://github.com/keyquesttech/Ratrig-Vcore-3-3.1-servo-nozzle-brush)
A servo attached nozzle brush.
 - [Endstops.](https://github.com/keyquesttech/3d_printer_endstops)
A collection of custom endstops for 3d printers or cnc machines. 
 - [Thermexp.](https://github.com/keyquesttech/Thermexp)
A PCB to add more thermistors to a klipper printer.

Chrome extensions:
 - [Youtube ads auto skip.](https://github.com/keyquesttech/chrome-extensions)
A chrome extension that emulates a click and auto skips youtube ads. Works even after adblock prevention measures.

Keyboards:
 - [Enclave.](https://github.com/keyquesttech/Enclave)
A custom mechanical switch macro pad. Works on QMK and can be used with klipper.
