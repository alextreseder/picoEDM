# PicoEDM

Minimalist Wire EDM for Hobbyists & Education. Designed with high accuracy and user experience in mind.

[**Join the Discord!!**](https://discord.gg/fNJQsGFzm4)

[**Pico Makes First Cut!**](https://youtube.com/shorts/JkDtk-GV0A8)

![Render Cover](https://github.com/alextreseder/picoEDM/blob/master/Images/pico5_render_cover.png)

## Concept

* Use components that are readily available worldwide (Amazon.com serving as benchmark)
* 360mm by 500mm footprint and 160mmX; 160mmY; 50mmZ travels
* Use a belted friction drive for wire handling
* Use a integrated driver closed loop stepper in torque mode to tension the wire
* Use inert materials for underwater assemblies
* Implement adjustable worktable for precision
* Use preloaded Tr8x2 nuts with integrated leadscrew steppers and mgn12 rails for motion
* Support the following features via a quick swap kinematic mount:
  * Sinker EDM end effector
  * Hole popper end effector

The firmware and spark generator is a seperate project supplied by
[GEDM](https://github.com/G-EDM)

## Project Status
```diff
+ PROJECT NOW IN BETA!
```
## Disclaimers

**EDM machines are dangerous**  
Beware electric shock and pinch points. Be prepared to activate emergency stop. Do not leave machine unattended. You are responsible for your own safety.

**Metric / Imperial**
The machine is nearly completely metric with the exception of the thickness of the laser cut parts. The nearest metric equivalents should work in all cases, but user should carefully review the CAD model before building to confirm.

## Currently In Progress

* Implement assited self threading

## Associated Projects
[NanoEDM - A higher quality machine](https://github.com/alextreseder/nanoEDM)

[KegStand - A consumables free water management system for EDM](https://github.com/alextreseder/kegstand)

## Future Goals
Future Development:
* Ultra-compact spark generator based on FGPA control technology

## Non-Goals
This is not a spark generator or firmware project, although I do have a high end spark generator under development. This is not an ultra precision machine. This is not a low precision machine.

## Latest Version Notes
Verison 6 (current) adds the following features: 
* Integrated electronics case
* Improved belt drive tensioning scheme

Verison 65 (legacy) adds the following features:
* Stepper brake pulley changed to 16 tooth
* Stepper brake mount geometry improved
* Magentetic kinematic coupler changed to bolted kinematic coupler. Magnet will be revisited
* Wire unspooling path components are  now modeled
* Machine now includes all features needed to run comfortably
* Project status updated to beta

Verison 62 (legacy) adds the following features (huge changes):
* Capstan brake changed from rotary damper brake to stepper motor brake via MKS Servo42D driver in torque mode
* All heat set thread inserts removed in favor of plastic screws 
* Redesigned wire end effector Z axis slider for better stability
* Doubled up the coupling magents to hold the end effector on better
* Again: Re-jointed the entire model from step files to clean things up and eliminate worthless dependancies
* Changed workholding strategy to magnetic base plate in tank. Any fixtures you want can be printed and attached with magnets

Verison 59 (legacy) adds the following features:
* Redesigned wire end effector Z axis slider to eliminate the need for milling
* Re-jointed the entire model from step files to clean things up and eliminate worthless dependancies
* Fixed subtle issues with water tank bumper geometry
* .f3d file now available
* Capstan bearings and shaft switched from 1/4" to M6 and 6x12x4 bearing


## Calculations
Desmos calculators have been made for various applications - they are not necessarily complete

[DESMOS - CAPSTAN EQUATION](https://www.desmos.com/calculator/trg4qsopa3)

## Donations
Bitcoin address: bc1qqp8etjvsmyyjqjm5unr0l4kj4qqpekz5jcclxv
