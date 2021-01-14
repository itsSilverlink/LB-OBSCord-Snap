# OBSCord-Snap
**A Lioranboard Extension that makes it possible to directly make screenshots from OBS and put them online in Discord.**

For it to work you need to have set up a webhook in your discord.  
Discord link: https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks

The Extension includes an example deck with 2 buttons. Practically it's ready to use.  
One button has a chat trigger and the other button has a channel points redemption trigger.  
  
![Example deck screenshot](https://github.com/XSilverlink/LB-OBSCord-Snap/blob/main/Screenshots/LioranBoard_Receiver_1.png)

Included examples:
```
Chat command: !obscordsnap
Channel Point Name: OBSCord Snap
```
Both of these can of course be changed to your liking.

Almost all the commands within these two buttons are commented and should be self-explanatory.  
I made it so you can fill in the variables on each row but you can of course put in the variables directly into the extension.

### Prerequisites
* [OBS Studio](https://obsproject.com/)
* [OBS Studio WebSocket](https://github.com/Palakis/obs-websocket/releases)
* [Lioranboard](https://obsproject.com/forum/resources/lioranboard-stream-deck-animator.862/)

### Variables
Variable Name | Explanation 
------------ | -------------
webhookURL* | Discord Web hook URL. [How to create one](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks)
obswsURL | OBS Websocket URL. Default is localhost:4444
obswsPass | OBS Websocket Password.
sourceName* | The source you want to take a screen off.
filePath* | The filepath location. This needs to be the absolute path ending with the extension png ex: C:/screenshot.png
optionalText | Add a text to the post that will be created on discord. This can be auto filled from chat or a channel point redeem.

**Variables marked with a * are REQUIRED variables and need to filled in!**
