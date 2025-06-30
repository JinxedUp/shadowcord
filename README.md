# shadowcord
**A fork of discord.py 1.7.3 originally made by Rapptz for selfbots and compatibility with python 3.13**

**Project's goal was to bring discord.py 1.7.3 to python 3.13 while improving the selfbot stealth aspect, new updates are not planned. if you would like to use an maintained discord libraries i recommend using** [Discord.py for bots](https://github.com/Rapptz/discord.py) **and** [Discord.py-self for selfbots](https://github.com/dolfies/discord.py-self) 

## Features
- fully compatible with python 3.13 and newer aiohttp versions
- improved stealthy requests for user accounts
- Rotates realistic browser User-Agent and X-Super-Properties headers for every request
- WebSocket Identify payload mimics real Discord clients/browsers, with randomized client/OS info

### This fork tries to not change that much how it works compared to discord.py, that means you can use the documentation for 1.7.3 created by Rapptz
[discord.py 1.7.3 documentation](https://discordpy.readthedocs.io/en/v1.7.3/)

Install shadowcord on your computer using:
```
pip install Shadowcord
```

Due to the fork being derived from discord.py 1.7.3, most selfbots written for that discord.py version will work with no changes.
