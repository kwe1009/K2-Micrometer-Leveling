# K2-Micrometer-Leveling

UNDER DEVELOPMENT - NOT READY FOR PRIMETIME - STAY TUNED

Get precise measurements using a micrometer to calibrate your K2 Plus bed.  I'm using a $20 one from https://amzn.to/3NqYsAP .  You will need to print the bracket from https://www.crealitycloud.com/model-detail/creality-k2-plus-dial-gauge-adapter .  

Check out the original at https://github.com/DnG-Crafts/K2-Leveling

No changes other than adding a micrometer and adjusting the bed height to accomodate.

Macros for the K2 Plus bed leveling video

[![https://www.youtube.com/watch?v=qKrKXGRXfWs](https://img.youtube.com/vi/qKrKXGRXfWs/0.jpg)](https://www.youtube.com/watch?v=qKrKXGRXfWs)

https://www.youtube.com/watch?v=qKrKXGRXfWs<br>

<br>

## NOTE
Firmware updates may remove the <b>bl_macros.cfg</b> file and the edit made to <b>printer.cfg</b><br>
If your macros are not in the list after a firmware update you will need to add the <b>bl_macros.cfg</b> and edit the <b>printer.cfg</b> again to restore them.
<br>

## XS3002
<img src=https://github.com/DnG-Crafts/K2-Leveling/blob/main/XS3002.jpg width=30% height=30%><br>
If you have installed this and update the printer you might get an error <b>XS3002</b> on screen.<br>
This means klipper has failed to start and is likely caused by the update removing the <b>bl_macros.cfg</b> but not the entry for it in the <b>printer.cfg</b> file.<br>
To solve it upload the <b>bl_macros.cfg</b> file again or remove the `[include bl_macros.cfg]` entry in <b>printer.cfg</b><br>
