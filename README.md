# DiscordRaidBots
Discord chat spam bots to raid Discord Servers.

# Information
Discord is a free chatting app for gamers and others alike, similar to other well known apps such as Skype, TeamSpeak, and Curse. Discord is unique with self server hosting, voice chat, and combines the features of all apps into one and makes them faster. Discord to me is a personal favorite app! I use it every day and has changed my life forever, I've met so many new friends on discord.

**Discord has an API for creating bots that can moderate Discord servers and Discord users alike, and there are limits to how this API is used called the API Terms of Service. This application does abuse the Discord API and should not be used directly. This was created for educational purposes only.**

# Getting Started

To use the raid bots, go into **/build/** folder and find the latest version number, download **build.zip** from there, extract to a folder and edit `config.json` to meet your specified needs.

In `config.json` you are going to find 2 peices of JSON data, **invite-code** and **owner-snowflake.**

1.**invite-code:** The invite code to join on launch (the bots' hub, essentially).
2.**owner-snowflake:** The snowflake (userID) of the owner. Used to provide admin only commands to the owner.

Within the same folder, you should find `token.txt` and `snowflake.txt`:

1.**token.txt:** The text file in which bot or user tokens are placed in.
2.**snowflake.txt:** The text file in which the snowflake(s) of the people who are whitelisted to use the bot's commands.

Snowflakes and tokens need to be formatted in a certain way that can be found [here](https://github.com/)

