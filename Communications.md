# Communications

This will go through some of the text-to-speech functions, announcements, briefings, notifications, and other communications options.

## Communication Card

On the home page, you will find a card with 3 tabs for different forms of communication.

### TTS

![House Announcement System](https://i.imgur.com/2s1KrQe.png)

This tab will allow you to manually send any text-to-speech message you want, to any room you want (or common areas, which is living room and basement) in any of our available Amazon Polly voices.

**NOTE:** This will ignore rooms in which someone is sleeping. If possible, it will redirect to other nearby rooms. Otherwise it will just do nothing.

### Text Notify

![Text Notification System](https://i.imgur.com/zBJcrpT.png)

This tab allows you to send a Home Assistant text notification to any phone or TV. There are three priority levels: Normal, Alert, and Critical. These priority levels only affect phones. They are as follows:

- Normal (lowest priority, **will not send** to people who are not home).
- Alert (higher priority, **will send** regardless of location).
- Critical (sends a notification marked as critical, which makes a very loud sound and pins the notification to the top of the target phone's notifications list until the recipient manually clears it...**DO NOT USE THIS UNLESS ABSOLUTELY NECESSARY**, as it is very disruptive).

TODO: add screenshot examples of notifications

### Reports

***Currently broken, will hopefully have a fix soon***

![Report System](https://i.imgur.com/u3ByH8i.png)

This tab will allow you to send *New Ideas* or *Bug Reports* directly to my Todoist board where I keep track of what I'm currently working on. This is a good way to make sure I don't forget the thing you want me to do.

## Housewide Announcements

![Announcements](https://i.imgur.com/ii5yADX.png)

This card can be found on the Global Scenes tab. This gives you premade TTS announcements that you can play to the entire house. I will add more as I think of them. If you have any ideas, please feel free to let me know.
