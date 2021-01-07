How to get emojis everywhere without nitro:

1. Install [PowerCord](https://github.com/HenryFBP/discord-with-free-emojis)
2. Install BetterDiscord plugin for PowerCord (Comes pre-installed)
3. Clone this repo into the BetterDiscord plugins folder (plugin for a plugin for a mod, wow)
   
   `CTRL-, -> Powercord -> Plugins -> ... -> Open Plugins Folder`
   
   Then, when your folder in command line is `powercord/src/Powercord/plugins/`, run `git clone https://github.com/HenryFBP/discord-with-free-emojis`
   
   Example commands:
   ```
   git clone https://github.com/powercord-org/powercord
   cd powercord
   npm i
   npm run plug
   cd src/Powercord/plugins/
   git clone https://github.com/HenryFBP/discord-with-free-emojis/
   ls 
   ```
   
   You should see a folder list like this:
   
   ```
   discord-with-free-emojis/   pc-codeblocks/  pc-connections/  pc-emojiUtility/  pc-heygirl/  pc-lmgtfy/  pc-moduleManager/  pc-rpc/  pc-settings/  pc-tags/
   pc-clickableEdits/          pc-commands/    pc-docs/         pc-hastebin/      pc-i18n/     pc-mock/    pc-notices/        pc-sdk/  pc-spotify/   pc-updater/
   ```

4. Restart Discord. Then, `CTRL-, -> Powercord -> BetterDiscord Plugins (...) -> Enable DiscordFreeEmojis`

# bdCompat

Compatibility layer for running BetterDiscord plugins in Powercord

[![Screenshot showing a list of BetterDiscord plugins](https://i.imgur.com/xaAOdSE.png)](https://i.imgur.com/xaAOdSE.png)

## Installation

Clone this repository to your Powercord install's plugins folder

```
git clone ...
```

## Installing BD plugins

<!-- Before you download and install any BD plugins, please take a look at the incompatibilites note on `INCOMPATIBILITIES.md` file -->

- Put the plugin in the `plugins` folder, if it doesn't exist then create one.
- Reload your Discord.
- Go to User Settings and head to the `BetterDiscord Plugins` section
- Enable the said plugin

#### edCompat? ED plugins support?
If you want EnhancedDiscord plugins support, you can use [EDPluginsLoader](https://github.com/Juby210/EDPluginsLoader) for BD.
