# Welcome to the NoseBot homepage


## What is NoseBot?

NoseBot is a Discord bot which currently provides the ability to send notifications to a Discord channel when a stream goes live.

Invite the nose [here] https://discordapp.com/oauth2/authorize?client_id=339505551115419648&scope=bot&permissions=268958784


## Commands

### Twitch Commands ###
- **```!!start```** - Tells the bot to start monitoring channels going live. (posts notifcations to the channel the command was posted)
- **```!!stop```** - Tells the bot to stop monitoring (**NOTE this may take up to 1 minute to fufil**)
- **```!!add <Twitch Name or link>```** - Adds the streamer to the list of channels to check
- **```!!remove <Twitch Name or link>```** - Removes the streamer from the list of channels to check. (can also use **!!delete**)
- **```!!notify <on/off> ```** - Adds the "notify" role to the user invoking the command. (Creates the role if it doesn't already exist)
- **```!!list ```** - Lists the streams that the bot is looking out for

### General Commands ###
- **```!!prefix <new prefix> ```** - Changes the default or existing prefix to the new one entered
- **```!!commands ```** - Displays the current list of commands
- **```!!addresponse <trigger> <response> ```** - The bot will watch out for the trigger word and reply with a response when seen
- **```!!deleteresponse <trigger> ```** - Deletes the response for that trigger
- **```!!responses ```** - Lists the current stored responses for this server


### About
NoseBot is written in C#, utilising Discord.Net to access Discord API.
The key features at the moment:
1. Add stream channels to follow
2. Notify a server when one of the channels go live
3. Create a notification role and add it to users who want it for live streams
4. Custom responses to trigger words

