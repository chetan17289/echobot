# echobot

A simple self-bot for echoing from one channel to another

Requires Node.js to be installed

## Config File:

### token:

* This is your login token for discord. If you dont your token or how to get it, google search 'find my discord self-bot token' There are many articles and videos.
### channels:

* 'color' is used for the embed, its not required and defaults to blue
* 'id' is not required. It is set automatically on the first message from channels that match 'guild' and 'channel' This reduces chances of losing the feed if the guild or channel name is changed.

### destChannel:
* This can be set here manually or by typing '.here' into the channel you wish to use as the destination channel - This event will be logged to the console.

## Getting started

Open a command prompt, powershell, or terminal window in the main directory and start the bot with the following command:

```
$ node discobot.js
```
  
# TODO:

* edit config with chat commands.

# From The Author

Feedback welcome! I am self taught and not very confident. If you know how to do the things I do better, let me know!