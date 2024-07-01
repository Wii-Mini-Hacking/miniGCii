# miniGCii
Restore GameCube controller ports to the Wii mini

Designed by @Devnol

This project allows for the readdition of the present but unimplemented GameCube controller ports on the Wii mini motherboard. Ports 1 and 4 are exposed easily as test pads but all 4 gpio lines are present next to the gpu.
The two ports this project readds are exposed through two 3.5mm TRRS jacks coming out the back of the console, right above the USB port.

Pinout is similar to those used by Madmorda or her [GameCube Classic](https://www.youtube.com/watch?v=_BxwS_uTKt4) and Wesk and CrazyGadget on the [GC Nano](https://bitbuilt.net/forums/index.php?threads/gc-nano-the-worlds-smallest-gamecube.5697/):

Pole | Tip | Ring1 | Ring2 | Sleeve
__________________________________
Use  | 5v rumble | 3.3v | Data | GND
Color | white | green | red | blue

## Project contents

This project consists of all the design files for the trrs jack PCB under [PCB](/PCB)
3D models for mounts will be added later

## LICENSE

This project is licensed under the TAPR Open Hardware License, which can be read [here](LICENSE.txt)
