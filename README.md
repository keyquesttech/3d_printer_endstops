<div align="center">
  <strong><h1>3D Printer Endstops</h1></strong>
</div>

<div align="center">
  A collection of custom-made endstop/limit switches for 3D printers or CNC machines.
</div>

<hr>

<div align="center">

| Endstop Durable | Endstop Cherry |
|--|--|
| <img src="https://raw.githubusercontent.com/keyquesttech/3d_printer_endstops/main/Imgs/durable_endstop.png" alt="Endstop Durable" width="228" style="margin-top: 10px;"> | <img src="https://raw.githubusercontent.com/keyquesttech/3d_printer_endstops/main/Imgs/cherry_endstop.png" alt="Endstop Cherry" width="228" style="margin-top: 10px;"> |

</div>

<div align="center">
  <strong><h1>Endstop Durable</h1></strong>
</div>

Inspired by the [RAT RIG ENDSTOP V1.1 - OMRON - NC](https://ratrig.com/catalog/product/view/id/1841/s/rat-rig-endstop-omron-nc/category/153/), this endstop includes all the features of the original:

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

A custom endstop for those looking to add some customization to their machine. This endstop uses standard 3-pin Cherry or Cherry-style mechanical switches. The benefits of using this type of switch over a traditional limit switch are:

 - Customization. You can use any style of switch you want as long as it's compatible with the PCB.
 - Customize the actuation force and travel.
 - Operating temperature, depending on switch brand, ranges from -40°C to +80°C.
 - 100 million operations (clicks).
 - Can add 3mm through-hole LED.

The downside of this design is that since Cherry MX switches only have two terminals, if ground fails, the switch won't trigger. However, an integrated LED will indicate any faults. This LED is separate from the trigger LED, which is through-hole and goes in the switch.
