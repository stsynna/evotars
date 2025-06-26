# Evotars Documentation for Twitch Streamers

One-stop doc to setup Evotars in your stream!

[Evotars Admin Panel](https://evotars.inferst.com) | [Evotars Wiki](https://github.com/stsynna/evotars/wiki) | [OBS Project Link](https://obsproject.com/forum/resources/evotars-%E2%80%93-lightweight-stream-avatars-for-chat.2146/) | [OBS Forum Link](https://obsproject.com/forum/threads/evotars-%E2%80%93-lightweight-stream-avatars-for-chat.185990/) | [Github Readme](https://github.com/inferst/evotars-app/blob/main/README.md)

<!-- This Wiki was consolidated and edited by @stsynna st.synna@gmail.com, please inform them for any errors/updates-->

***

## What are Evotars?

* Evotars are free browser-based avatars for Twitch chatters and viewers. It turns Twitch viewers and chatters into interactive game-like characters that react to chat and perform commands.
* It’s lightweight and easy to set up, perfect for small streamers who want to engage with their audience and grow their channel.




## Features

* **Active Commands**: Chatters can make evotar `!jump`, `!dash`, `!grow`, `!color`, and more.
* **Channel Rewards**: Chatters can use channel points to do actions like jump or change skin.
* **Chat Bubble and Emotes**: Evotars will show show bubble speeches and emotes, with 7TV emote support.
* **Customization**: Chatters can customize their avatar’s appearance — from color to skin.
* **Raid Support**: Raiders' evotars will 'fall' from the top to welcome the incoming community.
* **Easy to Use**: Web-based, so no downloads or complicated setup needed for OBS.




## How to Install in OBS

1. **Log into [Evotars Admin Panel](https://evotars.inferst.com) using your Twitch account.**

![image](https://evotars.inferst.com/_next/image?url=%2Fadmin.png&w=640&q=75)

2. **Copy Your Overlay URL**\
Under [Evotar Admin Panel](https://evotars.inferst.com) > [Preview](https://evotars.inferst.com/admin), click on the icon next to the blurred out link copy your stream's unique Evotars Overlay URL.\

![image](https://evotars.inferst.com/_next/image?url=%2Fsetup1.png&w=640&q=75)

3. **Add Evotars overlay in OBS:**\
a. In OBS, [create a new browser source](https://obsproject.com/kb/browser-source)\
b. Paste the Evotars Overlay URL.\
d. Set your desired width/height.\
e. Set the source setting FPS to 60 for smoother animation (optional).

![image](https://evotars.inferst.com/_next/image?url=%2Fsetup2.png&w=750&q=75)





## 💬 Using Chat Commands

Enable Twitch chat commands for evotars: [Evotar Admin Panel](https://evotars.inferst.com) > [Commands](https://evotars.inferst.com/admin/commands)


### Make Evotar Jump

Do the following to make your evotar jump 🆙.

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !jump is enabled as ✅ Active.

2. In Twitch stream chat, type !jump to make the evotar jump.



### Make Evotar Dash

Do the following to make your evotar run 🏃.

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !dash is enabled as ✅ Active.

2. In Twitch stream chat, type !dash to make the evotar dash.



###  Change Evotar Skin

Do the following to change your evotar skin 🎭.

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !skin is enabled as ✅ Active.

2. In Twitch stream chat, type !skin and skin name.** Example: `!skin agent`
Skins available (these can be selected under 'Skins' section): agent, cat, duck, duck_evil, dude, girl, nerd, nyan, owl, senior, sith, sponge 


### Change Evotar Color 

Do the following to change your evotar color 🌈.

1. In [Evotar Admin Panel > Commands](https://evotars.inferst.com/admin/commands), ensure that !color is enabled as ✅ Active.

2. **In Twitch stream chat, type !color and a color code.** Example: `!color red` or `!color #00ffcc`\
Suggested colors: White #FFFFFF | Silver #C0C0C0 | Gray #808080 | Black #000000 | Orange #FFA500 | Red #FF0000 | Green #008000 | Brown #A52A2A | Olive #808000 | Lime #00FF00 | Yellow #FFFF00 | Cyan #00FFFF | Aquamarine #7FFFD4 | Blue #0000FF | DarkBlue #00008B | LightBlue #ADD8E6 | Purple #800080 | Maroon #800000 | Magenta #FF00FF | Pink #FFC0CB





## 💰 Using Twitch Channel Points

Enable Twitch channel redeems for evotars: [Evotar Admin Panel](https://evotars.inferst.com) > [Twitch Rewards](https://evotars.inferst.com/admin/rewards)
* Action: Select from the pull-down menu
* Title: Name of the reward (this will be displayed in the Twitch channel)
* Cost: How many channel points is needed to redeem this reward


### Make Evotar Jump

1. In [Evotars Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click Add Custom Reward button.

2. In the form, select action 'Jump', fill in the blanks, and click on 'Add reward'.
Note: Velocity X and Y are optional.

3. Ensure the reward is enabled as ✅ Active.

4. In [Twitch Custom Rewards](https://help.twitch.tv/s/article/alerts-by-twitch-events?language=en_US#channelpoints), ensure channel point redemption for this is properly set up.



### Make Evotar Dash

1. In [Evotar Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click Add Custom Reward button.

2. In the form, select action 'Dash', fill in the blanks, and click on 'Add reward'.
Note: Force is optional.

3. Ensure the reward is enabled as ✅ Active.

4. In [Twitch Custom Rewards](https://help.twitch.tv/s/article/alerts-by-twitch-events?language=en_US#channelpoints), ensure channel point redemption for this is properly set up.



### Change Evotar Skin (aka 'Sprite')

1. In [Evotar Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click Add Custom Reward button.

2. In the form, select action 'Sprite', fill in the blanks, and click on 'Add reward'.
* User argument means the redeemer can choose their own.
* Value means the streamer can limit to certain skins. To allow various skins, use space in between skin names. Example: `cat duck nyan`
* Skins available (these can be selected under 'Skins' section): agent, cat, duck, duck_evil, dude, girl, nerd, nyan, owl, senior, sith, sponge 

3. Ensure the reward is enabled as ✅ Active.

4. In [Twitch Custom Rewards](https://help.twitch.tv/s/article/alerts-by-twitch-events?language=en_US#channelpoints), ensure channel point redemption for this is properly set up.\



### Change Evotar Color 

1. In [Evotar Admin Panel > Twitch Rewards](https://evotars.inferst.com/admin/rewards), click Add Custom Reward button.

2. In the form, select action 'Sprite', fill in the blanks, and click on 'Add reward'.
* User argument means the redeemer can choose their own.
* Value means the streamer can limit to certain colors. To allow various colors, use space in between color name/code. Example: `red yellow green`
Suggested colors: White #FFFFFF | Silver #C0C0C0 | Gray #808080 | Black #000000 | Orange #FFA500 | Red #FF0000 | Green #008000 | Brown #A52A2A | Olive #808000 | Lime #00FF00 | Yellow #FFFF00 | Cyan #00FFFF | Aquamarine #7FFFD4 | Blue #0000FF | DarkBlue #00008B | LightBlue #ADD8E6 | Purple #800080 | Maroon #800000 | Magenta #FF00FF | Pink #FFC0CB

3. Ensure the reward is enabled as ✅ Active.

4. In [Twitch Custom Rewards](https://help.twitch.tv/s/article/alerts-by-twitch-events?language=en_US#channelpoints), ensure channel point redemption for this is properly set up.\




## 🚫 Hiding Specific Users

You can hide specific users (e.g. bots) from having an evotar: [Evotar Admin Panel](https://evotars.inferst.com) > [Settings](https://evotars.inferst.com/admin/settings)

1. Under 'Users', type in Twitch username(s) you don't want evotars for. Use space to separate the usernames, e.g. user1 user2 user3

2. Refresh OBS browser source for the changes to take effect. This will reset the overlay.

