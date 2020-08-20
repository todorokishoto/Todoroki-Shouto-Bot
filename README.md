## Todoroki Shouto Discord Bot
[![Discord Bots](https://top.gg/api/widget/714330708365148190.svg)](https://top.gg/bot/714330708365148190)

## status
![discord.py](https://camo.githubusercontent.com/de59962dbfaf4f3824e3274391935ae6191e44f5/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f646973636f72642e70792e737667)
[![Discord Bots](https://top.gg/api/widget/owner/714330708365148190.svg)](https://top.gg/bot/714330708365148190)
[![Discord Bots](https://top.gg/api/widget/lib/714330708365148190.svg)](https://top.gg/bot/714330708365148190)
[![Discord Bots](https://top.gg/api/widget/upvotes/714330708365148190.svg)](https://top.gg/bot/714330708365148190)
[![Discord Bots](https://top.gg/api/widget/servers/714330708365148190.svg)](https://top.gg/bot/714330708365148190)
[![Discord Bots](https://top.gg/api/widget/status/714330708365148190.svg)](https://top.gg/bot/714330708365148190)

## Invite
> [Invite Me Here](https://discord.com/api/oauth2/authorize?client_id=714330708365148190&permissions=8&scope=bot)

## First the bot requires building in discord.py
``` python
import discord
import os
from discord.ext import commands

todo = commands.Bot(command_prefix="todo.")
```

##  Second Step :
``` python
# we need event, for reporting if bot is ready

@todo.event()
async def on_ready():
  print(f"Loginned as {bot.user.name} - {bot.user.id}")
  print(f"Server : {len(bot.guilds)}")

@todo.command()
async def ping(ctx):
  await ctx.send("Pong!")
```

##  Third Step :

``` python
SECRET = os.environ.get("TOKEN")
todo.login(SECRET)
```

## Token :
***Dont forget to put your Bot Token in the `.env` file***

> .env
``` env
TOKEN=YOU_BOT_TOKEN
```
 ## Visit Me On [top.gg](https://top.gg) !
> [Click and Click Here](https://top.gg/bot/714330708365148190)

## Fork This Repo 💕
> How to fork this repo? Just click [here!](https://github.com/todorokishoto/Todoroki-Shouto-Boto/fork) and fork!
