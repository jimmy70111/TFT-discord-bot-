# TFT-discord-bot-

Proof of Concept

 The following showcase me making an discord bot which later I can implement with the riot API to make the discord bot, Teamfight Tactics related

I make an bot with the following code-

import os
import random
import discord
from discord.ext import commands

bot = commands.Bot(command_prefix='/')

@bot.event
async def on_ready():
    print('Logged in as', bot.user.name)

@bot.command(name='hi', help='Bot says hi')
async def say_hi(ctx):
    await ctx.send('Hi')

bot.run('ODM0OTY2NDU0NDczNzE5ODM4.GuxXin.gEaNLog5Nl-519jTdV_7tLUxr-qsBNSjeOZJlM')


the following code allows my bot to say hi to me-

![image](https://github.com/jimmy70111/TFT-discord-bot-/assets/123014046/4c251f3b-a4ef-4e9d-be6c-8de261176e13)

