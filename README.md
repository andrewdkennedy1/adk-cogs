
ADK COGS
========

A collection of cogs for the [Red Discord Bot](https://github.com/Cog-Creators/Red-DiscordBot).

crumbl cog
----------

The `crumbl` cog allows users to retrieve information about Crumbl Cookies through the Red Discord Bot. To use the cog, simply enter the `!crumbl` command in a Discord server where the bot has been invited. The bot will then scrape the nutrition information from the Crumbl Cookies website and send an embed with the name, description, and image of a randomly selected cookie variety. The footer of the embed will also display any allergens contained in the cookie.


SteamID cog
----------

The SteamID cog allows users to enter the !SteamID command in a Discord server where the bot has been invited, followed by a mention of the Discord user they want to look up. The bot will then scrape the SteamID.io website for the Steam ID of the mentioned user and send it in a message.

Dependencies
------------

*   [aiohttp](https://aiohttp.readthedocs.io/en/stable/)
*   [asyncio](https://docs.python.org/3/library/asyncio.html)
*   [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
*   [discord.py](https://discordpy.readthedocs.io/en/latest/)

Contributing
------------

If you have an idea for a cog that you would like to see included in ADK COGS, feel free to open a pull request or issue on the [GitHub repository](https://github.com/adkcogs/adkcogs).
