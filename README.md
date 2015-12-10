## Lokio's Bots for Palringo ##
There's one thing for certain. This is coming soon.

### Bot Manager ###
This is the bot that allows people to pay it credits and receive a bot in the group of their choice. How would this work?
- A User private messages the Bot Manager
- Bot Manager asks what bot the user wants "Photo (# Credits), Music (# Credits) or Rules (# Credits)? Type "nvm" to stop!"
- A user either types nvm or types a bot.
- The bot then responds with "You have 2 minutes to send # credits to this bot! If you pay more than the cost, more time is added depending on how much more is sent."
- Once the credits are received, the bot goes to that room (if it isn't already there) and will respond to that command.

Now, the bots could be seperate users or just one. Seperate users wouldn't be a big deal, but hey. It would work best with one user but if we use multiple I'll have to make a nice old framework.

### The Plan ###
At the moment, I'm planning on using NodeJS and a socket library. I'll sort out the login mechanism eventually, allowing bots to change all kinds of things like status, name, profile image, ect.
