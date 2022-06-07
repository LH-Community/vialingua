# Vialingua

The Vialingua bot is used for communication between different linguistic parties on a Discord server.
The system is based on the idea that you can select your language when joining the server and then the channels are displayed in your language.


The config should be structured as follows:
```sh
Token: xxxxxxxxx.xxxxxxxx.xxxxxx
Prefix: (Slash Commands)
```
Assignment of the languages to the channels. Example:
```sh
German: ChannelID1, ChannelID2, ChannelID3
English: ChannelID4, ChannelID5, ChannelID6
```
All channels which should be linked together. The following example should bring clarity.
```sh
Channel group 1: ChannelID1, ChannelID4
Channel group 2 ChannelID2, ChannelID5
on and on like this
```
In this case, for example, ChannelID1 is the German chatroom and ChannelID4 is the English chatroom.
> To make the whole thing as user friendly as possible, I came up with the idea that for each chatting user a webhook is temporarily created with his name and profile picture which then sends the translated message. So you can also see with whom you are currently writing


> The bot only has to do the translation, it does not have to do the language assignment at the beginning.
