---
title: Lights
description: 
published: true
date: 2023-04-18T20:22:24.863Z
tags: 
editor: markdown
dateCreated: 2023-04-17T18:45:01.500Z
---

# Dashboard Tabs

**These controls are currently being considered for a redesign. If you have any ideas or input, let me know.**

![Floor Tabs](/pics/roomtabs.png)

There are 6 tabs after the Home tab. One for each floor of the house, one for outdoors, one for global scenes (or, things that do stuff in multiple parts of the house), and one for [climate](/Climate) control.

## Room Cards

![Room Cards](/pics/roomcard.png)

In the floor tabs, there is a card for each room on that floor.

There is a large icon at the top of each card...this will turn on/off all lights in that room. If you ***double tap*** the icon quickly, it will reset the lights to their default state (adaptive lighting, in most cases). If you are in a room with multiple individual lights, I have included toggle buttons for each light. Feel free to use those when you don't want EVERY light in the room to be on. When any lights in the room are on, you will see a dimmer that you can drag to manually set the brightness. If the room has RGB lighting, you can select color and color temperature (shades of white) as well.

![Dimmer](/pics/dimmer.png)
![Color Temp](/pics/colortemp.png)
![RGB Color](/pics/rgb.png)

If there are any fans, air conditioners, smartplug devices, sensors, or other smart accessories in a room, they will generally be on these cards as well.

There is a scenes dropdown box for each room as well. These are basically saved light settings for that room. Selecting ***"Adaptive"*** in the dropdown will do the same thing as the ***double tap*** mentioned above.

If you expand the ***More Settings*** section, you will find any extra settings for that room (Adaptive Lighting, Night Mode, and anything else that is room-specific) that I didn't want to clutter up the main card with. To continue using the Living Room example:

![More Settings](/pics/more_settings.png)

Most of the time you shouldn't need to use these, because automation will handle them as needed. But I have left them there for easy access in case they are needed, as well as just being able to see what's going on.

## Adaptive Lighting

Every room (okay, except the furnace room) has Adaptive Lighting, and in most cases it is the default mode. Adaptive Lighting gradually adjusts the lighting based on the time of day, relative to the sunrise/sunset times on that day for our location.

For ***white bulbs***, this will adjust the brightness to be higher during the day and lower as it gets darker outside, to be easier on the eyes.

For ***color bulbs***, this will do the same as above but will also adjust color temperature to be cooler during the day and warmer at night. This provides even MORE benefit because it is easier on the eyes, AND helps our body's natural rhythm to not be disturbed.

Hey, I might not be much of a sleeper, but for those who are...this is for you ;)

## Room Scenes

All scenes can be called with [Alexa](/Alexa#lighting) by saying "Alexa, turn on {scene} in {room}".

All rooms have the following scenes:

- Adaptive
- Bright
- Dimmed
- Nightlight

Additionally, rooms with color bulbs and/or multiple lights may have other scenes (in addition to the above). Those follow below, current as of 4/17/2023.

### Living Room

- Energize
- Concentrate
- Savanna Sunset
- Tropical Twilight
- Tokyo
- Forest Adventure
- Painted Sky

### Basement Studio

- Energize
- Concentrate
- Relax
- Purple
- Pink
- Kallen Reading
- Baby Is Napping
- Stairwell

### Front Porch

- Energize
- Concentrate
- St Patricks Day
- Halloween

### Upstairs Bathroom

- Single Nightlight

### Master Bedroom

- Front Nightlight
- Side Nightlight

### Kallen Bedroom

- Overhead Nightlight
- Wall Nightlight

## Global/Multiroom Scenes

These scenes will control multiple rooms and/or areas of the house. These are generally called with [Alexa](/Alexa#lighting) but most of them have UI buttons as well on the Global Scenes tab.

- Adaptive on First Floor (Reset first floor light settings)
- Adaptive on Second Floor (Reset second floor light settings)
- Evening Mode on First Floor (Set evening or "give me darkness" state on first floor)
- Evening Mode on Second Floor (Set evening or "give me darkness" state on second floor)
- Global On (Turn on every light in the house)
- Global Off (Turn off every light and smart switch/plug in the house)
- Max Brightness (Turn on every light in the house, disable Adaptive Lighting and set maximum brightness in all rooms)
