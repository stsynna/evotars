# Evotars Documentation for Twitch Streamers

One-stop doc to setup Evotars in your stream!

[Evotars Admin Panel](https://evotars.inferst.com) | [Evotars Wiki](https://github.com/stsynna/evotars/wiki) | [OBS Project Link](https://obsproject.com/forum/resources/evotars-%E2%80%93-lightweight-stream-avatars-for-chat.2146/) | [OBS Forum Link](https://obsproject.com/forum/threads/evotars-%E2%80%93-lightweight-stream-avatars-for-chat.185990/) | [Github Readme](https://github.com/inferst/evotars-app/blob/main/README.md)

<!-- This was consolidated and edited by @stsynna st.synna@gmail.com, please inform them for any errors/updates-->

***

## What are Evotars?

* Evotars are free browser-based avatars in Twitch streams, where viewers and chatters will turn into interactive game-like characters that react to chat and perform commands.
* It’s lightweight and easy to set up, perfect for small streamers who want to engage with their audience and grow their channel.




## Features

* **Active Commands**: Chatters can make evotar `!jump`, `!dash`, `!grow`, `!color`, and more.
* **Channel Rewards**: Chatters can use channel points to do actions like jump or change skin.
* **Chat Bubble and Emotes**: Evotars will show show bubble speeches and emotes, with 7TV emote support.
* **Customization**: Chatters can customize their avatar’s appearance — from color to skin.
* **Raid Support**: Raiders' evotars will 'fall' from the top to welcome the incoming community.
* **Easy to Use**: Web-based, so no downloads or complicated setup needed for OBS.




## How to Install in OBS

Reference: [Create a new OBS browser source](https://obsproject.com/kb/browser-source)

1. **Log into [Evotars Admin Panel](https://evotars.inferst.com) using your Twitch account.**

![image](https://evotars.inferst.com/_next/image?url=%2Fadmin.png&w=640&q=75)

2. **Copy Your Overlay URL**\
Under [Evotar Admin Panel](https://evotars.inferst.com) > [Preview](https://evotars.inferst.com/admin), click on the icon next to the blurred out link copy your stream's unique Evotars Overlay URL.\

![image](https://evotars.inferst.com/_next/image?url=%2Fsetup1.png&w=640&q=75)

3. **Add Evotars overlay in OBS:**\
a. In OBS, create a new browser source\
b. Paste the Evotars Overlay URL.\
d. Set your desired width/height.\
e. Set the source setting FPS to 60 for smoother animation (optional).

![image](https://evotars.inferst.com/_next/image?url=%2Fsetup2.png&w=750&q=75)





## 💬 Using Chat Commands

Enable Twitch chat commands for evotars via the [Evotar Admin Panel](https://evotars.inferst.com) here: [Commands](https://evotars.inferst.com/admin/commands)


### Make Evotar Jump

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !jump is enabled as ✅ Active.

2. In Twitch stream chat, type `!jump` to make the evotar jump. 🆙



### Make Evotar Dash

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !dash is enabled as ✅ Active.

2. In Twitch stream chat, type `_!dash_` to make the evotar dash. 🏃



###  Change Evotar Skin.

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !skin is enabled as ✅ Active.

2. In Twitch stream chat, type !skin and skin name to change evotar skin. 🎭 Example: `!skin agent`
* You can set which skins can be used in the [Skins section](https://evotars.inferst.com/admin/skins). Currently, these skins are available: agent, cat, duck, duck_evil, dude, girl, nerd, nyan, owl, senior, sith, sponge.


### Change Evotar Color 

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !color is enabled as ✅ Active.

2. In Twitch stream chat, type !color and a color code to change the evotar color. 🌈  Example: `!color red` or `!color #00ffcc`
* Suggested colors: white gray black brown olive green lime yellow cyan blue purple maroon pink red orange





## 💰 Using Twitch Channel Points

Enable Twitch channel redeems for evotars via the [Evotar Admin Panel](https://evotars.inferst.com) here: [Twitch Rewards](https://evotars.inferst.com/admin/rewards).
* Action: Select from the pull-down menu
* Title: Name of the reward (this will be displayed in the Twitch channel)
* Cost: How many channel points is needed to redeem this reward

Note: After these are enabled, ensure the channel point redemptions are also set up in [Twitch Custom Rewards](https://help.twitch.tv/s/article/alerts-by-twitch-events?language=en_US#channelpoints).


### **Make Evotar Jump**

1. In [Evotars Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click on 'Add Custom Reward' button.

2. In the form, select action 'Jump', fill in the blanks, and click on 'Add reward'.
* Velocity X and Y are optional.

3. Ensure the reward is enabled as ✅ Active.


### Make Evotar Dash

1. In [Evotar Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click on 'Add Custom Reward' button.

2. In the form, select action 'Dash', fill in the blanks, and click on 'Add reward'.
* Force is optional.

3. Ensure the reward is enabled as ✅ Active.


### Change Evotar Skin (aka 'Sprite')

1. In [Evotar Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click on 'Add Custom Reward' button.

2. In the form, select action 'Sprite', fill in the blanks, and click on 'Add reward'.
* User argument = redeemer can choose their own.
* Value = streamer can limit redeens to certain skins. Use space in between skin names. Example: `cat duck nyan`.
* You can set which skins can be used in the [Skins section](https://evotars.inferst.com/admin/skins). Currently, these skins are available: agent, cat, duck, duck_evil, dude, girl, nerd, nyan, owl, senior, sith, sponge.

3. Ensure the reward is enabled as ✅ Active.


### Change Evotar Color 

1. In [Evotar Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click on 'Add Custom Reward' button.

2. In the form, select action 'Sprite', fill in the blanks, and click on 'Add reward'.
* User argument = the redeemer can choose their own.
* Value = the streamer can limit redeems to specific colors. Use spaces in between colors (name or HEX code). Example: `red yellow green`
* Suggested colors: white gray black brown olive green lime yellow cyan blue purple maroon pink red orange

3. Ensure the reward is enabled as ✅ Active.




## 🚫 Hiding Specific Users

You can hide specific users (e.g. bots) from having an evotar to avoid cluttering up the overlay.

1. In [Evotar > Settings](https://evotars.inferst.com/admin/settings), under 'Users', type in Twitch username(s) you don't want evotars for. Use space to separate the usernames, e.g. user1 user2 user3

2. Refresh OBS browser source for the changes to take effect. This will reset the overlay.

