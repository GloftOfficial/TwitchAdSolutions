# TwitchAdSolutions

**Don't combine Twitch specific ad blockers.**

## Scripts

- vaft - [ublock](https://github.com/GloftOfficial/TwitchAdSolutions/raw/master/vaft/vaft-ublock-origin.js) / [userscript](https://github.com/GloftOfficial/TwitchAdSolutions/raw/master/vaft/vaft.user.js)
  - `Video Ad-Block, for Twitch` (fork) as a script.


## Applying a script (uBlock Origin)

- Navigate to the uBlock Origin Dashboard (the extension options)
- Under the `My filters` tab add `twitch.tv##+js(twitch-videoad)`.
- Under the `Settings` tab, enable `I am an advanced user`, then click the cog that appears. Modify the value of `userResourcesLocation` from `unset` to the full url of the solution you wish to use (if a url is already in use, add a space after the existing url). e.g. `userResourcesLocation https://github.com/pixeltris/TwitchAdSolutions/raw/master/vaft/vaft-ublock-origin.js` 
- To ensure uBlock Origin loads the script I recommend that you disable/enable the uBlock Origin extension (or restart your browser).

*To stop using a script remove the filter and make the url `unset`.*

## Applying a script (userscript)

**Use one of these funny monkey extentions, I recoment [Violent Monkey](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag)**

- Viewing one of the userscript files should prompt the given script to be added.