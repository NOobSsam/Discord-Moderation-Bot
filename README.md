 A small Discord moderation bot, without a command handler


# Getting started (For people who aren't used to Discord.js)


### Requirements
* Node.js
* A code editor (visual studio code, atom, notepad++ etc)
* Git

### Step zero, making a Discord bot account
Go to https://discord.com/developers and make an application. After creating your application, you should have the option to create a bot user.

### Step one, making the folder
Make a folder for which your bot's coding will be in


### Step two, opening powershell
Do shift + right click and select open powershell (or cmd depending on your PC)
![Step two](https://media.discordapp.net/attachments/804840017939660811/948037673866657812/gFSqpN0Y.png?width=829&height=548 "Step two")


### Step three, initiating, type `npm init`

### Step four, installing Discord.js
Now, you should type `npm install discord.js`, we are installing the discord.js module. Note: This will make a file called `package-lock.json` and a directory called `node_modules`, please don't delete that.

### Step five (I), getting your bot's token
Get your bots token. Reminder, bot tokens are key information that gives complete access to your bot.

### Step five (II), config.json
Place your bot's token **between** the quotation marks, you can also edit the prefix if you'd like.
![Step six](https://i.imgur.com/dy7OSYW.png "Step six")

### Step six, running your bot
Run your bot by typing `node bot` into your powershell/cmd

### Step seven, adding your bot to your server
Use this link and replace **client_id_here** with your actual client ID
https://discordapp.com/api/oauth2/authorize?client_id=client_id_here&permissions=0&scope=bot
# And your bot is running!
Enjoy the bot, updates are frequent so always return to replace your `bot.js` with the newest one.

---

### Any errors?
If you'd like to come to me personally, join the [support server](https://discord.gg/11pm)
