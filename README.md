# Hello! Today I will tell you how to get an active developer badge in the discord
![Alt-Developer Badge](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREt6DJ1OVMmDZCze67sft2tRlgaBSR1Ifyf97F8zxUqQ&s)

## Note! GitHub cannot accept more than 100 files. I have a lot of them. I did not upload them to this repository again + I had an error about the file that was hidden (I did not understand what it was). Click on the link (https://github.com/toptipus/activedeveloper/archive/refs/heads/main .zip) and download all the files from here.

### 1. Create and configure a bot
You need to create a reid bot by following the link (https://discord.com/developers/applications ). Click "New Applications", write the name and check the box.
In the column on the left, select "Bot".There we put all sliders on except "REQUIRES OAUTH2 CODE GRANT" and check the box next to "Administrator" below.
At the very top of the page, click "Reset token". 
![Alt-NodeJS](https://i.imgur.com/9VO9dhN.png)

Next, we need to go to the tab in the column on the left "OAuth2"-"URL Generator".
Among the buttons with ticks, we look for "bot" and poke to put a tick. Select "Administrator" below. Next, we generate a link to the bot. Click on the link and add the bot to your private discord server.

### 2. Config.json
Copy the token and go to the "config.json" file

```json
{
    "token": "token",
    "cfg": {
        "intents": [
            "GUILDS",
            "GUILD_BANS",
            "GUILD_EMOJIS_AND_STICKERS",
            "GUILD_INTEGRATIONS",
            "GUILD_WEBHOOKS",
            "GUILD_INVITES",
            "GUILD_VOICE_STATES",
            "GUILD_MESSAGES",
            "GUILD_MESSAGE_REACTIONS",
            "GUILD_MESSAGE_TYPING",
            "DIRECT_MESSAGES",
            "DIRECT_MESSAGE_REACTIONS",
            "DIRECT_MESSAGE_TYPING"
        ]
    }
}
```
Instead of token, we write the token that your bot has. Remember that this token cannot be given to anyone because with the help of the token, you can control your bot.

### 3. Installing NodeJS
Without installing NodeJS, you will not succeed. Click on the link (https://nodejs.org/en/download ) and download the installer. We launch it. During installation, just click next. **Do not change the installation path!**
![Alt-NodeJS](https://i.imgur.com/tdC3MGf.png)

### 4. Server Preparation
Go to the settings of your discord server. We find the "create a community" tab there. Creating
![Alt-Server](https://i.imgur.com/SV8Ezsj.png)

### 5. Launching the bot
In order for the bot to start working, you need to run the "start_bot.bat" file. In the console, you should have written "The name of your bot READY". 
![Alt-start bot](https://i.imgur.com/JcxGRaM.png)

Go to your server's chat and write the command "/ping". The bot will answer you "pong".

![Alt-start bot](https://i.imgur.com/vI54904.png)

### 6. Getting the badge
To get the badge, you need to follow the link (https://discord.com/developers/active-developer ) and press the button in the middle. The receiving process takes from 24 hours
![Alt-start bot](https://i.imgur.com/BBroFT0.png)
