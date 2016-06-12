---
title: How it works


toc_footers:
  - <a href='http://store.3dracers.com'>Buy 3DRacers</a>
  - <a href='https://github.com/3DRacers/3D-Models'>Download 3D models STL</a>
  - <a href='/docs/app.html'>Download iOS/Android App</a>
  - <a href='/editor'>Online Editor</a>

search: true
---

# How it works
> ![3DRacers Game](/docimages/cover2.jpg?raw=true "3DRacers Corvette Car")

Welcome to the documentation of 3DRacers.

`3DRacers` is the first real-life videogame that you can 3D Print and drive with your phone. 

Order online at the [Store](http://store.3dracers.com) and 3D-Print your car for free.

### Features
 * Videogame-like gameplay
 * Hundreds of Car bodies and accessories
 * Free App for up to 1,000 concurrent users
 * Arduino-compatible
 * [Open Source](https://github.com/3DRacers) and [Open Hardware](https://github.com/3DRacers/PilotBoard)

> ![3DRacers Game](/docimages/3dracers.gif?raw=true "3DRacers Corvette Car") 
 
If you can't find your answer here, ask the [Forums](http://forum.3dracers.com) for help. Also don't forget to look at the [Github Repository](https://github.com/3DRacers)

## Assembly instructions
 - 3D Print *(Easy print, no supports, ~2 Hours)* one of the [available models](#car-models) or Order a print online from 3DHubs
 - Follow the [Assembly Instructions](http://www.3dracers.com/start)
 
## Car Models
> ![3DRacers App](/docimages/cars.jpg?raw=true "3DRacers Cars")

 - Choose from: [Corvette](http://www.thingiverse.com/thing:599769), [Muscle Car](http://www.thingiverse.com/thing:706390), Pickup, DeLorean, Armageddon, Max Madness, Battle Tank
 - Preview and customize your car online with the [Online Editor](http://www.3dracers.com/editor)
 - Or pick one from the [community](http://forum.3dracers.com)
 - Create a [custom car model](http://www.3dracers.com/docs/design_new_car.html) from a 3D model
 
## Mobile App
> ![3DRacers App](/docimages/app_home.jpg?raw=true "3DRacers Corvette Car")

 - iOS: [Download from Itunes](https://itunes.apple.com/jp/app/3dracers/id1054404136?l=en&mt=8)
 - Android: [Download from Play Store](https://play.google.com/store/apps/details?id=com.Lib3DRacers.Lib3DRacers)
 - Read the [Guide and Tips](http://www.3dracers.com/docs/app.html)
 
## PilotBoard
 - [PilotBoard Guide](http://www.3dracers.com/docs/board.html)

## Code
3DRacers Pilot control board comes pre-programmed, but can be programmed with Arduino IDE. 
It's compatible with a wide range of sensors and devices and supports shields.

 - [Quick start](http://www.3dracers.com/docs/code.html) and [Reference](http://www.3dracers.com/docs/code.html#reference)
 - [Download the Arduino library](https://github.com/3DRacers/Lib3DRacers) for 3DRacers
 - [Download the support drivers](https://github.com/3DRacers/3DRacersArduino) for Arduino IDE
 - Shields: [Accelerator Shield](http://www.3dracers.com/), [Proto Shield](http://www.3dracers.com/)
 - [Fork on Github](https://github.com/3DRacers)
 
## Create a new car model
 - Use the [template](https://www.tinkercad.com/things/eMrdzYMlwBJ-3dracers-model-kit) with Tinkercad to transform your 3D model to a functional 3DRacers
 - Read the [How To](http://www.3dracers.com/docs/design_new_car.html) with Tinkercad and Blender
 
## Open Hardware
 - Get the [schematic and PCBs layout on Github](https://github.com/3DRacers/PilotBoard) for Eagle CAD
 - Fork the [Arduino sketch](https://github.com/3DRacers/Lib3DRacers) and [Bootloader](https://github.com/3DRacers/3DRacersArduino)

## Tech Specs

 - `ATMega32U4` processor
 - Motor driver for 2 DC Motors `DRV8835`
 - Bluetooth Low Energy 4.1 radio
 - LiPo battery charger `LM73831`
 - Drive 2 Servo, 2 DC Motors, 8 digital/analog IN/OUT Pins
 - On board high efficency DC motor
 - RGB Led `WS2812`
 - IR Gate sensor
 - Programmable via USB
 - Shield support: `Accelerometer/Gyro Shield`, `Proto Shield`
