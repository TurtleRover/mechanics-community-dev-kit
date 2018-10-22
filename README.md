<p align="center">
  <a href="http://turtlerover.com" alt="Turtle Rover"><img src="https://avatars3.githubusercontent.com/u/36553642?s=84&v=4" alt="Turtle Rover" /></a>
</p>
<h1 align="center">Mechanics: Community DevKit</h1>
<h4 align="center">A basic development kit. Includes 3D files and ready-to-print files</h4>

<p align="center">
  <a href="https://github.com/TurtleRover/mechanics-community-dev-kit/releases">
    <img src="https://img.shields.io/github/release/TurtleRover/mechanics-community-dev-kit.svg" alt="Release"></a>
  <a href="https://github.com/TurtleRover/mechanics-community-dev-kit/blob/master/LICENSE">
      <img src="https://img.shields.io/github/license/TurtleRover/mechanics-community-dev-kit.svg">
  </a>
  <a href="https://twitter.com/TurtleRover">
    <img src="https://img.shields.io/twitter/follow/TurtleRover.svg?style=social&label=Follow">
  </a>
</p>
<p align="center">
  <a href="http://turtlerover.com" alt="Website">Website</a> |
  <a href="https://www.facebook.com/TurtleRover/" alt="Facebook">Facebook</a> |
  <a href="https://www.youtube.com/channel/UCxukvEct3wP0S5FACa3uelA" alt="YouTube">YouTube</a>
</p>

# List of parts

## 3D-printed:
* 1x 03001 - Electronics box base
* 1x 03002 - Electronics box cover
* 1x 03003 - Mounting plate
* 2x 03005 - Support foot (2 pcs.)
* 2x 03006 - Electronics support (2 pcs.)

## Components:
* 1x [Shield](https://github.com/TurtleRover/electronics-shield)

## Fasteners:
* 6x M4x12 imbus screw
* 4x M4x12 threaded distance
* 8x M4x8 imbus screw
* 6x M4 hex-nut (or M4 square nut)
* 8x M2,5x8 philips-head screw
* 4x M2,5x20 threaded distance
* (optional) 2x Cable bushing SKINTOP ST-M LappKabel 53111000 (bushing + o-ring + nut)
* (optional) 5x Rubber bushing M12

Cables and connectors:

- 1x Female connector WEIPU SP1310-S7II with tape
- 1x Female connector WEIPU SP1310-S9II with tape
- 1x Interface cable with WEIPU SP1310-P7II
- 1x Interface cable with WEIPU SP1310-P9II
- 1x 2-pin green connector
- 1x 8-pin green connector

Not included and needed:
- 1x RaspberryPi 3B+
- 1x microSD card (8 GB)
- 1x Power adapter (12-24 DC; at least 1A)

Tools needed:
- 1x microSD-to-SD card adapter
- 1x Philips-head screwdriver
- 1x Imbus screwdriver no. 3
- 1x Flat wrench no. 7
- 1x Double-sided tape
- 1x WD-40 can (or other lubricant)
- 1x Computer with a SD card slot

Getting started

Software upload:
1. Download a newest TurtleOS SD card image: https://drive.google.com/open?id=16_0G9UX7-NvIJFdP9mQDNYPm05ayJ65J
2. Download Etcher (software to burn images to SD cards): https://etcher.io/
3. Using a microSD-to-SD card adapter, plug the card to your computer.
4. Turn on Etcher and select the image. Select your drive and click 'Flash!'.
5. It should take ca. 15 min to upload the image to the card.
6. After a successful upload, unplug the microSD card and put it to your RaspberryPi.

Casing assembly:
1. Using 4x M4x8 imbus screws attach 4x M4x12 distances to a 03001 casing base (4 holes seen from the bottom)
2. Take 1x 7-pin WEIPU female connector and 1x 9-pin WEIPU female connector and, gently twisting their tapes, unscrew and separate nuts from them.
3. Push the connectors in slated holes on the bottom of 03001 base. Put the base in front of you with bottom up and SKINTOP bushings facing you. Left slated hole fits 9-pin WEIPU female connector and right hole 7-pin WEIPU female connector. Put nuts on the cables and screw them with your hand.
4. Using 4x M4x8 imbus screws assemble the casing (through distances) to 03003 mounting plate.
5. Using 1x M4x12 imbus screw and 1x M4 hex-nut (or square nut) assemble each of 03005 support foot to 03003 mounting plate front holes the ones facting rounded corners - left and right one).
6. Attach 2x 03005 electronics support to Turtle Hat using 4x M2,5x8 philips-head screws and 4x M2,5x20 threaded distances. The support should face the side of Turtle logo printed on the Hat.
7. Put Turtle Hat on top of RaspberryPi pins and push it gently to connect.
8. Screw remaining 4x M2,5x8 philips-head screws into RaspberryPi mounting holes.
9. Plug Turtle Hat USB connector to any socket in RaspberryPi.
10. Plug 8-pin green connector to Turtle Hat (you'll use it in the future to connect up to 4x DC motors)
11. Connect external power adapter cables to 2-pin green male connector (follow the mating connector description on the board).
12. Thread the power cable through on of two holes in the rear ofthe 03001 base.
13. Connect the 2-pin male connector to 2-pin female connetor on Turtle Hat.
14. Connect 7-pin and 9-pin WEIPU tape connectors to mating sockets in Turtle Hat.
15. Using double-sided tape - attach the legs of 3005 electronics support to the casing. Leave some place for USB connectors that could be connected to RaspberryPi.
16. Close the case with a 03002 cover using 4x M4x12 imbus screws and 4x M4 hex-head nuts (or square nuts).

(optional)
There are (optional) items in the kit to provide some kind of watertightness to the casing. As it's tougher to attach external cables with the bushings in place, use them only after you get accustomed with the kit.
(optional) assembly:
1. Screw 2x SKINTOP Cable bushings using dedicated nuts and o-rings to rear panel of the casing base.
2. Push 5x Rubber bushing M12 using lubricant (WD-40 or other) into 4x side holes and 1x hole in the front (the one on the side of front panel)

Next:
1. Plug the power adapter (=turn on the Kit) and wait ca. 2-3 minutes for TurtleOS to set its WiFi.
2. On your computer, find a WiFi named: `TurtleRover` (password: `password123`).
3. Type: http://turtle.rover or http://192.168.100.1 in a browser (remember about 'http://').

Have fun!


Additional description:
- Supports 1x USB camera, 4x DC motors and 3x servos in the pre-built interface
- RaspberryPi internal WiFi enabled
- WiFi name: `TurtleRover` ; password: `password123`
- Type: http://turtle.rover or http://192.168.100.1 in a browser


Open electronics schemes:
https://github.com/TurtleRover/electronics-shield/releases

Everything is licensed under MIT Open-source License. Feel free to use it, but remember to give credits on what you do.

Any help needed? Write: contact@turtlerover.com

www.turtlerover.com
