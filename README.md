# NSFWBot
A Discord bot which provides NSFW images

# Run the bot

- Create the file `token`, put your Discord token in this file
- Run `node main.js`

# Installation
This part explains you how to make the bot run at boot

It is **only for systemd**

- Copy this folder (NSFWBot) in `/opt`
- Copy nsfwbot.service in `/lib/systemd/system/`
- Run `# systemctl enable nsfwbot`

The bot should now start with your computer :)
