# Mobile Dashboard

Recently, I designed a mobile dashboard. This will be a lot friendlier to use on your phones, and will be the focus of most of my dashboard development going forward.

## Banner Card

![Banner Card](/pics/mobile_banner.png)

This card will show you some current weather information. If you tap on this card, it will take you to the main (non-mobile) dashboard.

## Popup Cards

Admin Version

![Mobile Popup Buttons - Admin](/pics/mobile_popup_buttons.png)

Kallen Version

![Mobile Popup Buttons - Kallen](/pics/mobile_popup_buttons_kallen.png)

These cards have various popups to access certain information, automations, or controls at a glance without having to search for them. If you are an admin, you will see buttons to bring up the med tracker cards for each person who has one. If you are Kallen, these are replaced by your timer controls.

## Mobile Briefing

![Mobile Briefing Card](/pics/mobile_briefing_card.png)

This card will show text briefings relevant to each person in the household. This is still very much work-in-progress, so if you have any suggestions for improvements ***please*** let me know.

## Room Cards

Examples:

![Mobile Basement Card](/pics/mobile_basement_card.png)
![Mobile Living Room Card](/pics/mobile_living_room_card.png)
![Mobile Master Bedroom Card](/pics/mobile_master_bedroom_card.png)
![Mobile Emma Bedroom Card](/pics/mobile_emma_bedroom_card.png)

These cards will contain all of the controls for a given room. Additionally, in the upper right corner, they will include any relevant sensor information for that room. This includes motion, windows, doors, climate control status, temperature where available, etc. In some cases, clicking on a button will bring up a popup card with further settings (the master bedroom A/C is an example of this). The scene buttons will also bring up a popup menu for easy selection of scenes.

Kids' bedroom cards work a bit differently. As you can see on Emma's bedroom card, it is locked. This is because she is sleeping (sleep switch is on). I have done this to prevent accidentally pressing buttons while someone is sleeping in the room.

To use controls on these cards, simply tap the card and a popup will ask if you're sure you want to unlock it. Accept this, and the card will unlock for a short time so that you can change what you need. It will then re-lock itself.

When the sleep switch is off, the card is not locked.

The master bedroom card currently does not lock in any situation.
