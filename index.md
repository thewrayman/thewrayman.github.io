# Welcome to the NoseBot homepage


## What is NoseBot?

NoseBot is a Discord bot to help help servers engage in a more interactive environment and allow servers to track Twitch streams

[![Build status](https://ci.appveyor.com/api/projects/status/1j75hrccq5gtex4m?svg=true)](https://ci.appveyor.com/project/thewrayman/nosebot)

Invite the nose [here](https://discordapp.com/oauth2/authorize?client_id=339505551115419648&scope=bot&permissions=268958784)



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

### Analytics Commands ###
- **```!!stats user <user tag> ```** - Displays that user's top 5 words in the last month
- **```!!stats all ```** - Displays the top word each user found in that server's chat log

This section will be expanded to include some ML and AI technology based on chat logs


### About
NoseBot is written in C#, utilising Discord.Net to access Discord API.
The key features at the moment:
1. Add stream channels to follow
2. Notify a server when one of the channels go live
3. Create a notification role and add it to users who want it for live streams
4. Custom responses to trigger words
5. Chat logging to enable chat analytics
6. Get information on the most used words in the server

