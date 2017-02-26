# DiscordRaidBots
Discord chat server raiding spam bots, used to spam servers and raid them with all sorts of stuff, maybe even to ratelimit other bots.

Discord is a free chatting app for gamers and others alike, similar to other well known apps such as Skype, TeamSpeak, and Curse. Discord is unique with self server hosting, voice chat, and combines the features of all apps into one and makes them faster. Discord to me is a personal favorite app! I use it every day and has changed my life forever, I've met so many new friends on discord.

**Discord has an API for creating bots that can moderate Discord servers and Discord users alike, and there are limits to how this API is used called the API Terms of Service. This application does abuse the Discord API and should not be used directly. This was created for educational purposes only.**

# Getting Started

To use the raid bots, go into **`/build/`** folder and find the latest version number, download **`build.zip`** from there, extract to a folder and edit `config.json` to meet your specified needs.

In `config.json` you are going to find 2 peices of JSON data, **invite-code** and **owner-snowflake.**

1. **invite-code:** The invite code to join on launch (the bots' hub, essentially).
2. **owner-snowflake:** The snowflake (userID) of the owner. Used to provide admin only commands to the owner.

Within the same folder, you should find `token.txt` and `snowflake.txt`:

1. **token.txt:** The text file in which bot or user tokens are placed in.
2. **snowflake.txt:** The text file in which the snowflake(s) of the people who are whitelisted to use the bot's commands.

Snowflakes and tokens need to be formatted in a certain way that can be found [here](https://github.com/)

# For Developers

If you would like to commit or modify the source, feel free to do so! Please be sure to contact me when you do so becuase I'd love to hear about what you did!

Discord raid bots were coded in C# using the Discord.NET wrapper for the Discord API created by RougeExcepetion and some credit to foxbot.
(The wrapper can be found [here](https://github.com/RogueException/Discord.Net) or on NuGet.)

# License

I'm releasing this under the GNU Public License 3.0.

>The GNU General Public License is a free, copyleft license for software and other kinds of works.
>
>The licenses for most software and other practical works are designed to take away your freedom to share and change the works. By >contrast, the GNU General Public License is intended to guarantee your freedom to share and change all versions of a program--to make >sure it remains free software for all its users. We, the Free Software Foundation, use the GNU General Public License for most of our >software; it applies also to any other work released this way by its authors. You can apply it to your programs, too.
>
>When we speak of free software, we are referring to freedom, not price. Our General Public Licenses are designed to make sure that you >have the freedom to distribute copies of free software (and charge for them if you wish), that you receive source code or can get it if >you want it, that you can change the software or use pieces of it in new free programs, and that you know you can do these things.

More information can be found on the GNU Public License 3.0 at [**`/LICENSE`**](https://github.com/ejectedmatrix/DiscordRaidBots/blob/master/LICENSE)

# Credits

bin-sama or bin-senpai for writing and updating most of the source.
Neura for starting the source and creating the most basic version.
Kai for some ideas for it
HotShot - For the idea of remote messages and being a really good friend
Singular and Mvulcan - for the idea of having a Web Panel
