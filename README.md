# BD-Server-Themes
Allow individual servers to use specific themes.

THIS WILL ONLY WORK FOR BETTER DISCORD USERS

## How To Use
1. Install [BetterDiscord](https://betterdiscord.net/home/) if you don't already have it.
2. Download [serverTheme.plugin.js](https://raw.githubusercontent.com/IRDeNial/BD-Server-Themes/master/serverTheme.plugin.js)
3. Put it in your plugins directory (Just open it from the client, can vary between users).
4. Restart BetterDiscord

## How to create themes
1. In Discord, open your settings, go to Appearance, and enable **Developer Mode**.
2. In Discord, right click on the server that you want to create a theme for.  Then click **"Copy ID"**.  This will give you the server ID.
    * This will be referred to as {{ServerID}}.
3. In your themes folder, create a new file and name it **{{ServerID}}.servertheme.css**
4. In this file, put any CSS that you want to be applied to the individual server.
5. Save
6. Rejoin the server

## Images
![https://share.md5.xyz/LNs14701940579Da.gif](https://share.md5.xyz/LNs14701940579Da.gif)

## To Do List
* Write auto-update routine
* Allow live changing of CSS so switching servers is not required in order to update

## Contributors
* [IRDeNial](https://github.com/IRDeNial/)

## Contribution Guidelines
* Document **ALL** code contributions
  * Anything undocumented will be ignored until full documentation is provided
  * **TEST** your code first.  Do not blindly contribute.
  * Do NOT do a pull request into master, do it on **[dev](https://github.com/IRDeNial/BD-Server-Themes/tree/dev)** instead.
    * Your pull requests will be merged into master at each iteration if accepted.
