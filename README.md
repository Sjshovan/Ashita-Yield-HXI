**Author:** [Sjshovan (LoTekkie)](https://github.com/LoTekkie)  
**Version:** v1.0


# Yield HXI

> An Ashita v4 addon for HorizonXI that tracks gathering metrics and provides editable prices, alerts, reports, and in-game settings.

<img src="https://i.postimg.cc/rsWfXXN8/yield-1-0-1.png..." data-canonical-src="https://i.postimg.cc/rsWfXXN8/yield-1-0-1.png" width="175" height="350" />
<img src="https://i.postimg.cc/3RkL1Dy0/yield-1-0-2.png..." data-canonical-src="https://i.postimg.cc/3RkL1Dy0/yield-1-0-2.png" width="400" height="350" />
<img src="https://i.postimg.cc/FKWW0xKQ/yield-1-0-3.png..." data-canonical-src="https://i.postimg.cc/FKWW0xKQ/yield-1-0-3.png" width="400" height="350" />
<img src="https://i.postimg.cc/bJ4mBNbC/yield-1-0-4.png..." data-canonical-src="https://i.postimg.cc/bJ4mBNbC/yield-1-0-4.png" width="400" height="350" />
<img src="https://i.postimg.cc/pVnGnzbg/yield-1-0-5.png..." data-canonical-src="https://i.postimg.cc/pVnGnzbg/yield-1-0-5.png" width="400" height="350" />
<img src="https://i.postimg.cc/Fs5Pbzh1/yield-1-0-6.png..." data-canonical-src="https://i.postimg.cc/Fs5Pbzh1/yield-1-0-6.png" width="400" height="350" />  

### Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Upgrading](#upgrading)
- [Aliases](#aliases)
- [Usage](#usage)
- [Commands](#commands)
- [Support](#support)
- [Change Log](#change-log)
- [Known Issues](#known-issues)
- [License](#license)

___
### Prerequisites
1. [Final Fantasy XI Online](http://www.playonline.com/ff11us/index.shtml)
2. Ashita v4
3. HorizonXI-compatible addon environment

___
### Installation

1. Place this folder at `addons/yield`.
2. Start Ashita.
3. Load the addon with:

    /addon load yield

**Autoloading**

Add `/addon load yield` to your Ashita startup script if you want the addon loaded automatically.

___
### Upgrading

1. Exit Final Fantasy XI.
2. Replace the existing `addons/yield` folder with the updated version.
3. If the UI or settings behave unexpectedly after a larger update, back up and then clear the addon settings for a clean rebuild.
4. Reload the addon with `/addon reload yield`.

___
### Aliases
The following aliases are available to Yield commands:    

**yield:** yld  
**unload:** u  
**reload:** r  
**find:** f  
**about:** a  
**help:** h  
 
 ___
### Usage

Manually load the addon with:
    
    /addon load yield  

Yield HXI supports harvesting, excavating, logging, mining, digging, fishing, and clamming with configurable pricing, alerts, colors, reports, and settings through the in-game UI.

___    
### Commands

**help**

Displays available Yield commands. Below are the equivalent ways of calling the command:

    /yield help
    /yld help
    /yield h
    /yld h
    
**unload**

Unloads the Yield addon. Below are the equivalent ways of calling the command:
    
    /yield unload
    /yld unload
    /yield u
    /yld u
    
**reload**

Reloads the Yield addon. Below are the equivalent ways of calling the command:
    
    /yield reload
    /yld reload
    /yield r
    /yld r

**find**

Positions the Yield window to the top left corner of your screen. Below are the equivalent ways of calling the command:
    
    /yield find
    /yld find
    /yield f
    /yld f

**about**

Displays information about the Yield addon. Below are the equivalent ways of calling the command:
    
    /yield about
    /yld about
    /yield a
    /yld a
    
___
### Support
**Having Issues with this addon?**
* Please report them here: [https://github.com/Sjshovan/Ashita-Yield/issues](https://github.com/Sjshovan/Ashita-Yield/issues).
  
**Have something to say?**
* Send feedback through the in-app Feedback page or email: <Sjshovan@Gmail.com>

**Want to stay in the loop with my work?**
* Repository: <https://github.com/Sjshovan/Ashita-Yield>
* Discord: <https://discord.gg/3FbepVGh>

**Wanna toss a coin to your modder?**
* You can do so here: <https://www.Paypal.me/Sjshovan>

___
### Change Log
**v1.0.0** - 03/23/2026 (HorizonXI Edition)
- Ported the addon to Ashita v4 for the current HorizonXI codebase.
- Refreshed the settings, help, about, and feedback flows for the current UI.
- Restored and cleaned the public command surface for the current release.
- Updated NPC base pricing defaults from LandSandBoat item data.
- Cleaned up internal helpers, naming, and documentation for a presentable `v1.0` release.

___
### Known Issues

- Large game window or UI scale changes may still require a quick position reset with `/yield find`.
- Some behavior still depends on server-specific system messages, so parsing should be verified against the live HorizonXI environment after major server-side changes.

### License

Copyright 2026, [Sjshovan (LoTekkie)](https://github.com/LoTekkie).
Released under the [BSD License](LICENSE).

***
