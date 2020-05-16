TF2-Scripts
===========

The fork of Lyrositor's original script which removes broken features and focusing on gameplay.

**Original Github Link:** [Lyrositor/TF2-Scripts](https://github.com/Lyrositor/TF2-Scripts)

**Original GameBanana Link:** [TF2 Scripts - Script Collection](http://tf2.gamebanana.com/scripts/8373)

## Features ##
Most features are usable by all classes, but a few are class-specific.
If you have feedback about this script, please go ahead! I will consider about your opinion.

- **Debug Output:** prints debug messages to the screen using captions (such as rocket jump and so on).
- **Auto Crouch-Jump:** automatically makes you crouch-jump when playing the spacebar. 
- **Loadout Switch:** binds 4 `Shift` key combinations to each loadout.
- **Netgraph:** displays the netgraph on the score screen (`Tab` key).
- **Null-Cancelling Movement Script:** a classic script which lets you immediately change direction.
- **NEW! Wait command checker:** Allows you to check wait command availability for you. Enabled by default.
- **NEW! Medic Uber ready bind:** sends a team message that ubercharge is ready, and also faking uber by playing other voice command. Recommend to press when reach 98%.
- **NEW! Callout bind:** Use your keypad to use Callout bind. Pressing Number key while holding `0(INS)` key on your keypad will allow you to use Spycheck Callout.
- **NEW! Medic Radar:** Pressing `Shift` key will toggle the Medic Radar. Useful when finding other team.
- **NEW! Auto Medigun:** You don't need to press your left click anymore! Now including auto medi-gun script which allows you to keep medigun active. Might break if server does not allow wait command. To disable auto medi-gun, press Number 1, 3 key or use wheel to disable it.
- **NEW! Sniper Precision Zoom:** Pressing and holding `Shift` key while zoomed in will slow down the precision speed.
- **Suicide Explosion:** makes you explode at the touch of a `Delete` key.
- **Viewmodel Toggling:** toggles display of the active weapon at the press of the `Insert` key.
- **Zooming:** zooms in and out when pressing `F`.
- **Engineer: Building Bindings:** Use arrow keys to build your buildings instantly. Note: The previous building will be demolished if you press same key again. UpArrow: Sentry, DownArrow: Dispenser, LeftArrow: Teleporter Entrance, RightArrow: Teleporter Exit
- **Soldier: Rocket Jump:** a simple rocket jump script bound to `MOUSE2` when toggled on (use `R` to toggle). Does not provide optimal jump, but is a reliable way to rocket jump. Aim the rocket launcher at the ground before clicking.

### Settings ###
TF2-Scripts comes with several settings used to disable certain undesired features; edit them in `cfg\_settings.cfg`:

- `AUTO_CROUCH_JUMP`
- `CLEAR_CONSOLE_ON_START`
- `DEBUG_OUTPUT_ON_START`
- `NULL_CANCELLING`
- `LOADOUT_SWITCH`
- `SHOW_NETGRAPH`
- `SOLDIER_ROCKET_JUMP`
- `SUICIDE_EXPLOSION`
- `ZOOM_IN_HIDE_WEAPON`
- `ZOOM_IN_SENSITIVITY`
- `ZOOM_OUT_SENSITIVITY`

## Installation ##
To install, locate your Team Fortress 2 installation's `custom` folder (usually located at `C:\Program Files (x86)\Steam\SteamApps\common\Team Fortress 2\tf\custom` on Windows), then copy-and-paste the `TF2-Scripts` there.
To install with mastercomfig, download the mastercomfig version of TF2 Script on [release page](https://github.com/AhRoon/TF2-Scripts/releases), extract and locate your Team Fortress 2 installation's `custom` folder (usually located at `C:\Program Files (x86)\Steam\SteamApps\common\Team Fortress 2\tf\custom` on Windows), then copy-and-paste the `TF2-Scripts-mastercomfig` folder on there.

## Credits ##
The scripts bundled together would not have been possibly were it not for the scripts and tutorials provided by the following people:

- [Lyrositor](https://github.com/Lyrositor) for making this awesome TF2 Script Collection,
- The [Team Fortress 2 Wiki](http://wiki.teamfortress.com) contributors for their scripting tutorials,
- [Zoolooman](http://wiki.teamfortress.com/wiki/User:Zoolooman) for his `echo` [tutorial](http://wiki.teamfortress.com/wiki/User:Zoolooman/Scripting),
- INsane for his [developer console font file information](http://www.dodbits.com/dods/index.php/source-graphics/source-gui-hud-tutorials/33-console-font-color-and-size),
- [clovervidia](http://steamcommunity.com/id/clovervidia/) for his [captions tutorials](http://www.reddit.com/r/tf2scripthelp/wiki/captions),
- povohat.au for his [null-cancelling script](http://ozfortress.com/showpost.php?p=624355),
- stabby stabby for his [zoom script](http://steamcommunity.com/groups/stabbyvideo/discussions/0/846963165458399532/),
- josh33901 for his rocket jump suggestion,
- Chuzzy for his [Sniper Precision Script](https://gamebanana.com/scripts/7726),
- BootlegJoel for his [Keypad Callout Script](https://gamebanana.com/scripts/10026),
- Chdata, Stabby Stabby for his [Improved Crouch Jump Script](https://gamebanana.com/scripts/7982),
- povohat, Perkzitos for his [Null-Cancelling Movement Script](https://gamebanana.com/scripts/9842).

If you are the author of this script and need to be in credit or want some script to be removed, please let me know on issue tracker, then I will fix the credit or remove your script.
