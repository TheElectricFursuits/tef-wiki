# Amenophis

## Bio

I created the Elecrtic fursuit chat circa 2015 when I decided to make a fursuit with LEDs in the head for Burning Man. I discovered a few like minded folks and decided to create a group so we could share ideas, help each other and showcase mutually our projects.

I have a CS/EE degree, worked on computer architecture, Operating Systems, Performance and Cloud Computing back ends. But that's all useless stuff: I picked up interest in Arduino development when a friend gave me a board he bought and gave up on. Afterwards I discovered addressable LEDs and used them for my fursuit. I was not happy with the LED libraries as they were not designed to be performant, compact and minimize memory consumption so I wrote FAB_LED. I have been focussing on wearable LEDs and small projects where power and invisible controllers ae the main focus. I've been using mostly AVR AtTiny85 chips.

Currently I've taken on decorations/scenics for conventions as a lead and focussing on large builds like sets or props, and less on the geeky side of things. My goal is to provide interractive immersive experiences, and do so on a showstring budget for the convention.

I bought some ESP32's so at some point I will need to find projects using their features, and maybe make it an excuse to port my library(ies) to ARM chips.

## Past coding projects

- [FAB_LED](https://github.com/sonyhome/FAB_LED), a programmable LED library for AVR. Data is bitbanged, and LED data array and code is separated to make usage more flexible. For example it can handle multiple LED types, and can handle updating multiple LED strips in parallel, or handle infinite LED strips if their pattern can be made with a simple code loop (like a rainbow), or handle color mapping, to reduce memory usage or do coloring tricks.
- [DigitalIO](https://github.com/sonyhome/DigitalIO), an attempt at a unified library to handle IOs like switches, sensors etc. The goal is to provide a simple API and hide the logic to make the sensor data reliable (debounce etc), stateful so people don't need to learn how to handle concurrent events ("many things at the same time").
- [SerialMenu](https://github.com/sonyhome/SerialMenu), a library to make menus on the serial console to simplify text UI development. I used it on:
- [PWM_Servomotor_Animatronics_with_Adafruit_PCA9685](https://github.com/sonyhome/PWM_Servomotor_Animatronics_with_Adafruit_PCA9685) a piece of code that manages like 4 servos on an I2C shield, to animate the ears of an animatronic lion head, as a free collab with a maker. The code has a debug mode that allows finding the usable range of the servos to store in a config table. The actual build was never finished.

## Costumes Electronics

- Laissez Ferret

## Art projects

- Warp Core
- Life Trips
- [Lightning Fixture](https://github.com/sonyhome/lightning_ornament)

## Skillset

- Basic electronics
- Arduino
- CS & EE
- Construction
- Rigging
- Theater sets & props design
- Project Management
- Party hosting
- Teaching
- Getting shit done

