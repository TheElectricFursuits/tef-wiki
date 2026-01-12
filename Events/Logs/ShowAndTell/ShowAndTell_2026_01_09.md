## Talk 1: Xasin's BeatSync IMU-Based dance/rhythm synchronisation

Xasin presented his tech to use a simple Phase-Locked-Loop algorithm based on acellerometer data to provide low-computation-effort, highly stable beat timings. This method provides very simple ways to synchronize lighting effects with music, walking, and other rhythmic motions, without needing complex audio processing or such.

The algorithm smoothly times LED effects to the natural motions of the wearer, allowing for very interactive effects especially during dances <3

Example video and further explanation can be found here:
https://lucidragons.de/projects/lucy/features/beat_sync.md

## Talk 2: Mariday's SkyFrame presentation

Mariday talks about their SkyFrame system, which is an elegant Fursuit-Component networking layer running on FastDDS. This system allows various processes of code to efficiently communicate, either on a local machine or via network with low effort.

This system is meant to make for more easily interoperatable pieces of code, which can be swapped out and transparently run on various code types, threads, processes or even entirely separate machines, and thusly to allow for plug-and-play operation of many different components for sensors, fursuit controllers, LED rendering and LED output devices.

Link to the project can be found here: https://github.com/themariday/skyframe

## Talk 3: Tretron's Fursuit Electrical Safety

Tretron gives a talk about fursuit electrical safety considerations. Most importantly here is considerations of wire thickness and wire-derating for denser fur areas, to ensure that no cable will melt at currents below what it is fused at, *especially* for sensors that *usually* do not draw a lot but could act as their own short circuit source.

Link to their own blog writeup here: TODO

## Talk 4: Wick's LED rendering system

Wick (@dragon_axo) shows their python-based LED rendering system. This setup tightly couples a Teensy (driving a ton of high density WS2812 LED matrices) to a computer, and allows the transmission of images and animated effects from the PC to the panels.

The program features a fully fledged UI that allows for drag&drop arrangement of the panels, allows for the placement of a "background image" to be transmitted to the LED panels, as well as the creation of glow effects that can flow over the LEDs, all of which is live-rendered and transmitted to the panels in realtime.

They are also in the process of making various mix&match LED panels that can be used to arrange a large variety of panel shapes and effects, with their most visible example being that of their recognizable fully animated LED panels.

## Talk 5: Kelson's website shenanigans

Kelson presented their project to provide live website feed data from their ESP32 project. This involves some JavaScript `async` shenanigans, alongside various protocol discussions.
The talk also glanced over options such as MQTT, Chromium's WebBLE for direct connection between browser and a BLE device, and viser.

### Noteworthy post-talk discussion:

- Headstraps! https://www.kiwidesign.com/products/k4-comfort-head-strap