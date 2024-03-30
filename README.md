# Q1-Pro Standard Operating Procedures (SOP)

## Please read this document in its entirety to learn how to use the Q1-Pro 3d printer safely and responsibly.
-------------------------------
This Document will provide step-by-step instructions for operating the Qidi Q1-Pro 3D-Printer utilizing OrcaSlicer to ensure safe and effecient printing and outline any rules and procedures that must be followed by any user to use this 3D-Printer

This Document will cover:

* Storage and use
* Material specific Machine configurations
* Accessing print profiles and webUI from OrcaSlicer
* Preparing the printer for Print Jobs
* Printer specific features & hazards
* Rules & Misc. Procedures
----------
  Machine Specific firmware and documentation can be found on the [`Qidi Q1-ProGithub Page`](https://github.com/QIDITECH/QIDI_Q1_Pro)
  
  Slicer documentation can be found on the [`Orca Slicer Github Page`](https://github.com/SoftFever/OrcaSlicer)

-------------


## Storage and use
While printer is not in use it should be stored with top cover installed, front door closed, and power for the machine switched off. (Power Switch for machine is in the rear of the machine, next to the power input cord).
Only authorized users should operate the Qidi Q1-Pro 3D-Printer, all unathorized users' use should be accompanied by the assistance of an authorized user.

## Material specific Machine configuration
During printing of low temperature, low hazard materials, the top cover of the printer should be removed and the front door should be opened for proper part cooling and air circulation. 
Leaving the enclosure assembled may also lead to heat creep in the extrusion system resulting in blockages of the filament path and failed prints.

These filaments inculde but are not limited to:

* PLA
* PETG
* TPU
* Above Filament's reinforced counterparts i.e. Carbon Fiber, Wood Filled, Etc.
-----
Higher Temperature filaments may benefit from the use of the enclosed build area of this 3D-Printer. These filaments may be susceptible to draft or cooling related warping, causing prints to or even detach from the build plate.

These filaments include but are not limited to:
* ABS
* ASA
* PolyCarbonate
* PA6/PA12 Nylons
* Above Filament's reinforced counterparts i.e. Carbon Fiber, Glass Filled, Etc.

Some filaments are also likely to release VOCs (Volatile Organic Compounds) while printing. These plastics should only be printed with the enclosure completely sealed and the chamber filter installed and activated.

## Accessing print profiles and webUI from OrcaSlicer
OrcaSlicer has already been Pre-Configured on the designated 3D-Printing Computer at Spark Studio. It will provide easy slicing and device access, as well as gcode streaming without the use of any SD-Card Or USB Flash-Drive.
Filament profiles will also be provided and documented. This github will be a storage location for any tuned printer or filament profiles that are created.

Orca Slicer can also be downloaded and configured easily on your own computers to send files and monitor print status from within the space. There is no cloud functionality built into the Q1-Pro. 
As of currently the Q1-Pro profile is only natively included in the nightly build of [`Orca Slicer`](https://github.com/SoftFever/OrcaSlicer/releases/tag/nightly-builds). Once it is added to an official release, the software version at the space, as well as this link will be updated.

[`Instructions`](/OrcaLearning) can be found in this repo in [/OrcaLearning]

## Preparing the printer for Print Jobs and removing prints from the build surface
Before printing any Job, the Build area must be prepared. The build plate may need to be coated with hairspray, glue stick, or tape before printing, depending on the filament selected.
Users must ensure the build plate is installed before any print is started. It may also be beneficial to preheat the printer's chamber for an extended time after a long pause between prints, or before printing with filaments more prone to warping. 
The Chamber heater can be enabled via the fluidd interface within OrcaSlicer's Device page, or from the web. It can be found in the "Thermals" Section of the page labeled as "Chamber". Here you will also find heating controls for the Printbed and Extruder.

Prints may only be removed from the build surface after the bed has cooled to ambient temperature. Periodic washing of the build surface may be necessary. 
It can be cleaned afteer every 2-3 prints with 99% isopropyl alcohol and a lint free cloth, though a deep cleaning with dish soap and hot water is required every 20-25 prints to prevent buildup.

## Printer specific features & hazards
The Qidi Q1-Pro is equipped with a Chamber Heater. This heater gets upwards of 100°c (212°f) and is supplied with 120v AC. Both of these features could injure users who come into contact with the heater, wether it be intentional or accidental.
This printer is also equipped with a Core-XY Motion system. This system is very fast and very powerful and could injure users.

It is imperative users keep the the 3D-Printer clear of any tools, loose articles of clothing or jewelry, or body parts during any printing operation.


## Other Rules & Misc. Procedures


* No part of the Qidi Q1-Pro 3D-Printer (firmware, software, hardware, Etc.) will be modified by any authorized or unauthorized users without explicit permission from the Designated Commitee, or tool Director. 
Modification authorization will be granted to a specific project to be completed by a specific user. 

Modifications to any part of the printer may result in termination of that printer's warranty per Qidi's guidelines.
![Screenshot of ssh Warning](/readme_elements/SSH_Warning_Message.png "Screenshot of SSH Warning Message")
