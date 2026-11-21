# Lili's Plugins

Dalamud plugins I made for myself and a few friends. They are private and not on the official list, so they install through a custom repository.

If you got here some other way: feedback and criticism are welcome, but I don't take requests.

## Install

1. In game, type `/xlsettings` and open the **Experimental** tab.
2. Under **Custom Plugin Repositories**, paste this link and click the **+**:
   ```
   https://raw.githubusercontent.com/ThePoyer/lilis-plugins/main/repo.json
   ```
3. Click **Save and Close**, then open `/xlplugins` and search for "Lili".

Updates show up in `/xlplugins` like any other plugin.

## The plugins

**Lili's Fate** (`/llf`) farms FATEs in the field zones of Shadowbringers, Endwalker and Dawntrail. You need vnavmesh, RotationSolver Reborn and BossModReborn installed, and the game client in English. AutoRetainer, Lifestream and Lili's Auto Pinch are optional. Spending bicolor gemstones starts off. If you turn it on and the vendor isn't unlocked for you, nothing is bought and the farm stops in town.

**Lili's Auto Pinch** (`/lla`) adds an Auto Pinch button to the retainer list and to the sell list. It undercuts your listings and ignores bait prices. Turn Dagobert off first, or both buttons end up in the same spot. There's an optional Region tab: when the rest of your region sells an item much cheaper than your world, your listing goes to the average of the two, so it sells faster without dumping it. That option is off by default, and it's the only thing that goes online: it asks Universalis for prices, sending item IDs and your world name, nothing else.

**Lili's Patch of All the Things** (`/llp`) has small fixes for other plugins, each with its own toggle. All of them start off.

**Lili's Little Tricks** (`/llt`) has small tricks for the game itself, also one toggle each and all off at first. The first one logs you into your last character when the game starts and again after a disconnect. Log in by hand once so it knows who you are, and hold Shift on the title screen if you want to stop it. VIWI's AutoLogin sends everyone in NA to Aether since patch 7.58. This one doesn't. If a future patch breaks the Data Center again, you can pick yours by hand in the window.

**Lili's Probe** (`/llpr`) is for friends who test the others with me. It records what your character does to a file on your PC and never touches the game or the internet. When something looks wrong, open `/llpr`, write what happened, pick when it happened (it can be a while ago) and press Report. Later press Export and send me the .zip it makes. Your character name, world and Windows user name are swapped out of that file. Recordings older than 7 days are deleted on their own, and you can change that in the window.

## Good to know

Automation breaks the game's terms of service. Use it with moderation, and don't leave it running for hours while you're away.
