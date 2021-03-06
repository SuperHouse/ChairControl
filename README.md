Chair Control Breakout
=======================
Copyright 2018 SuperHouse Automation Pty Ltd <www.superhouse.tv>  
Designed by Jonathan Oxer

Connects between an electric wheelchair input device and the chair
controller, so that the input device can be read by an Arduino and
redirected to another system.

The output can be isolated so that the chair won't receive the input
signals, preventing it from moving while the input is being used for
another purpose such as controlling a computer or remote control
device.

The Arduino can send the output to either a connected USB host such
as a computer, or to the trainer port on a Flysky radio remote control
so the wheelchair controls can be used to fly a drone or drive a
remote control car.

A second input device can be connected simultaneously, so that a total
of four axes can be read. For example, a pair of low-force hall-effect
joysticks attached to a wheelchair could be used to fly a drone.

Features:

 * 2 x input device connections.
 * 1 x input device pass-through output
 * 1 x mini-DIN 4 pin output for PPM connection to Flysky transmitter
 * Mounting headers for an Arduino
 * Derives 12V power from the host wheelchair controller

More information is available at:

  http://www.superhouse.tv/chairbreakout


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to the project.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
