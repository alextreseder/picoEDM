# PicoEDM

PicoEDM is a minimalist but well performing multi-process EDM machine made from readily available components and household tools. The PicoEDM has a quick change end effector mount allowing the user to easily swap between WEDM, DEDM, and Fast Hole.
Pico's namesake is a nod to the tiny footprint of the machine. Its big brother is Nano, and Micro was already taken:)

![Machine Front](https://github.com/alextreseder/picoEDM/blob/master/renders/PicoEDM_Machine_Front.png)

## Disclaimer

**EDM machines are dangerous**  
Beware electric shock and pinch points. Be prepared to activate emergency stop. Do not leave machine unattended. You are responsible for your own safety.

## Latest Version

Verison 58 adds the following features:
* Redesigned wire end effector
* Changed motion system components for ease of assembly and manufacture
* Redesigned the water tank mounting scheme
* Added worktable and its adjustment screws

[v58 CAD DOWNLOAD](https://github.com/alextreseder/picoEDM/blob/master/CAD/PicoEDMv58.step)

## Project Status
alpha

## Documentation
For documentation, please [**VISIT THE PROJECT WIKI**](https://github.com/alextreseder/picoEDM/wiki).

## Concept
The current scope of the project: 
* Use components that are readily available worldwide (Amazon.com serving as benchmark)
* 360mm by 500mm footprint and 170mmX; 110mmY; 50mmZ travels
* Trade comfort features for lower cost
* Use a rotary damper as a capstan brake to tension the wire
* Use a 3D printer filiment extruder as a wire pinch roller
* Use stainless on ALL submerged fasteners and structure components for machine longevity
* Implement adjustable worktable for precision
* Use preloaded Tr8x2 nuts with integrated leadscrew steppers and LM12UU bearings for motion
* Support the following modifications:
  * Sinker EDM end effector
  * Hole popper end effector

The recommended firmware and spark generator is supplied by
[GEDM](https://github.com/G-EDM)

## Future Goals
Future Development:
* Ultra-compact spark generator
* Water filtration system contained in a 5 gallon bucket

## Non-Goals
This is not a spark generator or firmware project, although I do have a high end spark generator under development. This is not an ultra precision machine. For a machine with a much higher performance ceiling - see my
[NANOEDM](https://github.com/alextreseder/nanoEDM)

## Calculations
Desmos calculators have been made for various applications - they are not necessarily complete

[DESMOS - CAPSTAN EQUATION](https://www.desmos.com/calculator/trg4qsopa3)

#### Thanks:

README template inspired heavily by:
[CLOUGH42 ELS](https://github.com/clough42/electronic-leadscrew)
