# OBSCord-Snap
**A Lioranboard Extension that makes it possible to directly make screenshots from OBS and put them online in Discord.**

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

**Variables marked with a * are REQUIRED variables and need to filled in!**
