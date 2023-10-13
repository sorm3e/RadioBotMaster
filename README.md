# RadioBot
A simple Discord radio streaming bot

> **Important**
> This bot is against the Discord TOS and only for educational use

# Installation

Replace the token, channel id and the stream url (optional)

(Volume 0-100)
```json
{
  "token" : "YOUR_TOKEN",
  "channelID" : "YOUR_CHANNEL_ID",
  "streamURL" : "http://stream.laut.fm/80er",
  "volume" : 10
}
```

1. Install nodejs & npm
2. Go into the bots folder
3. `npm install`
4. `node index.js`

> **Note**  
> You need to invite the bot to your server first


If you have problems with the installation of the libraries or when running the bot, make sure you are using an up to date nodejs version like v19.x
You also maybe need to run `sudo apt-get install ffmpeg` separately
