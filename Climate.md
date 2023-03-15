# Climate Control Tab

On the climate control tab, we currently have four things:

- **Climate Feed**
- **Master Bedroom**
- **Emma Bedroom**
- **Climate On**

## Climate Feed

![Climate Feed](https://i.imgur.com/KiWbI9y.png)

This card provides a scrollable timeline of the last state change for each climate-related entity. This can be useful information to see at a glance what is running and what isn't, and what the current settings are (if applicable). This will only show devices that are currently available (so no air conditioners in the winter).

## Master Bedroom

![Master Bedroom](https://i.imgur.com/L7zV2Nr.png)

This card is where the Master Bedroom's climate control settings live. Currently, this is the only room in the house with a smart air conditioner.

Pretty self-explanatory...you can enable/disable the entire automation of climate settings for the master bedroom. You can also set whether the A/C is in fact installed...you would turn this off in winter when the AC is put away, which will make the automation ignore all A/C related nodes and only control the fan.

The sliders at the bottom control the various temperatures that will be automatically set for the room at different phases of the day. At **wakeup time** (or "Alexa, good morning"), the daytime flow will be run. If the forecast high for the day is above 80, it will set the temperature to the **"Daytime Temp"** set by the slider (if not, it will just turn off the A/C). At the **"master bedroom cooling"** time (or "Alexa, give me darkness"), it will turn on the A/C and/or disable Eco mode as needed, and set the **"Night Temp"** from the slider. When the **goodnight** button from Global Scenes is pressed or "Alexa, goodnight" is activated, it will run the late night flow. The climate portion of that flow will set the A/C to the **bedtime temp** from the slider.

Additionally, you can tap on any of the slider titles (eg, Daytime Temp) which will manually configure the room to that setting.

## Emma Bedroom

![Emma Bedroom](https://i.imgur.com/04JWGgj.png)

This card is a lot simpler, because her A/C is not smart. It's just on a smart plug.

## Climate On

![Climate On](https://i.imgur.com/ZpGacWL.png)

This card is easy. It simply displays any climate entities that are currently **ON**. You can use this to quickly turn off fans that are left on, or change the A/C settings.
