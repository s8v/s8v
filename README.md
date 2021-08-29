<h1 align=center>Hi! I'm Max / Vxi 👋</h1>

*Main / Owner / Developer at <a href="https://vxi.one">Vxi.one / Mememail</a> · Developer*

![Visitor](https://visitor-badge.laobi.icu/badge?page_id=s8v.s8v)

### Languages I use.
<p>
  <img alt="Google Cloud Platform" src="https://img.shields.io/badge/-Google_Cloud_Platform-1a73e8?style=flat-square&logo=google-cloud&logoColor=white" />
  <img alt="PowerShell" src="https://img.shields.io/badge/-PowerShell-5391FE?style=flat-square&logo=PowerShell&logoColor=white" />
  <img alt="Visual Studio" src="https://img.shields.io/badge/-Visual_Studio-750098?style=flat-square&logo=visual-studio&logoColor=white" />
  <img alt="C Sharp" src="https://img.shields.io/badge/-C_Sharp-8006c7?style=flat-square&logo=c-sharp&logoColor=white" />
  <img alt=".NET" src="https://img.shields.io/badge/-.NET-5C2D91?style=flat-square&logo=.net&logoColor=white" />
  <img alt="git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img alt="npm" src="https://img.shields.io/badge/-NPM-CB3837?style=flat-square&logo=npm&logoColor=white" />
  <img alt="html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="NginX" src="https://img.shields.io/badge/-NginX-269539?style=flat-square&logo=NginX&logoColor=white" />
  <img alt="Nodejs" src="https://img.shields.io/badge/-Nodejs-43853d?style=flat-square&logo=Node.js&logoColor=white" />
  <img alt="Python3" src="https://img.shields.io/badge/-Python3-cf9006?style=flat-square&logo=Python&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/-Linux-CD9834?style=flat-square&logo=Linux&logoColor=white" />
  <img alt="Json" src="https://img.shields.io/badge/-Json-c2a721?style=flat-square&logo=json&logoColor=white" />
</p>

### Get to know me...
```py
import discord
from discord.ext import commands

client = commands.Bot(command_prefix="s!")
client.remove_command("help")

@client.command()
async def primarylanguages(ctx):
    langem = discord.Embed(
        title="Max's Languages",
        description="""Languages I Use!
        Python
        C-Sharp
        HTML (If you count that as a language :))
        JavaScript
        """,
        color=discord.Colour.dark_purple()
    )
    await ctx.send(embed = langem)

@client.command()
async def aboutme(ctx):
    aboutem = discord.Embed(
        title="Some Info About Me :)",
        description="My Name: Max / Vxi\nMy Discord Name Is: Max?#1234\nTwitter Name: sslmalware\nMy Location: Britan\nMy Hobbies: Coding, Gaming, Scooting And Watching Movies",
        color=discord.Colour.dark_purple()
    )
    await ctx.send(embed = aboutem)

client.run("Token")
```
