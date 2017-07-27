## Welcome to the NoseBot homepage


### What is NoseBot?

NoseBot is a Discord bot which currently provides the ability to send notifications to a Discord channel when a stream goes live.


### Commands

- ``` **!!start** ``` - Tells the bot to start monitoring channels going live. (posts notifcations to the channel the command was posted)
- ``` **!!add** _\<Twitch Name or link>_ ``` - Adds the streamer to the list of channels to check
- ``` **!!remove** _\<Twitch Name or link>_ ``` - Removes the streamer from the list of channels to check. (can also use **!!delete**)
- ``` markdown **!!list** ``` - Displays the current list of channels being monitored


### About
NoseBot is written in C#, utilising Discord.Net to access Discord API.
The key features at the moment:
1. Add stream channels to follow
2. Notify a server when one of the channels go live


