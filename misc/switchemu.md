# Eden and Ryujinx setup guide (windows only for now)

### Prerequisites
- Download from https://eden-emu.dev/downloads / https://ryujinx.app/download
- Download firmware from https://github.com/THZoria/NX_Firmware/releases/download/22.5.0/Firmware.22.5.0.zip
- Download keys from https://files.prodkeys.net/ProdKeys.NET-v22.5.0.zip and extract `prod.keys`
- Download roms - [good sites](#roms)
- Set up folders
   ```
    ├───prod.keys     (temporary)
    ├───firmware.zip  (temporary)
    │
    ├───amiibo (optional - Eden only)
    │   └───[amiibofolders]
    │
    ├───[emulator]
    │   ├───user (Eden)
    │   └───portable (ryujinx)
    │
    └───games
        │
        └───[gamename]
                game.nsp
    ```
- (Optional - Eden only) Download Amiibo from https://redd.it/12dqc51
  - make sure to `ctrl f` `image` and delete the useless image and `!Essential files` folders

## [Eden](#eden) | [Ryujinx](#ryujinx)

## Eden
### Setup
Create the `user` folder mentioned above if you havent already
1. On first boot Eden will ask you to install keys. Select `prod.keys` and hit ok. Can also be added in the `Tools` menu
2. To install firmware select `Tools > Install Firmware > From ZIP` and select the firmware zip
3. Double click the big folder icon and select the `games` folder. After it's added, right click the path and select `Scan subfolders`
4. Hit `ctrl ,` or `Emulation > configure`.  
Now we rapidfire settings. You can hover over them to see what they do if you want.
    ```  
    General
      External Content > add games folder
      Hotkeys > Your choice
      Web > Your choice
    System
      Language > Your choice
      Region > Yours if you're using your own dumped games
      Device Name > Your choice
      Profiles > Your choice
      Network > Enable Airplane Mode
    Graphics
      API > Vulkan
      Resolution > Higher if you have beefy computer
      Anti-Aliasing > SMAA
      Advanced > GPU mode > Accurate
      Anisotropic Filtering > Automatic or 16x
      Force maximum clocks
      Sync to framerate of video playback
      Enable buffer history
      Extras > Enable asynchronous presentation
      Enable asynchronous shader compilation
    Controls
      Input Device > Your controller
       (Note: Some games only work with Joycons (fuck you Boxville) in that case, set Pro Controller to Dual Joycons)
      Sets automatically after setting one button.
        (Note: Xbox controllers have no motion controls. Mods exist for games that require motion such as a shrine in BotW, search online)
      Advanced > Controller navigation off (if it gets annoying)
      Use random Amibbo ID (if using Amiibo)
      Hit OK
    ```
## Ryujinx
### Setup
Create the `portable` folder mentioned above if you havent already
1. Install keys by going `Actions > Install Keys > .KEYS`
2. Install firmware by going `Actions > Install Firmware > .ZIP`
3. Go `Options > Disable Show Console` if it's enabled
4. Now configuration.
    ```
    Options
      Change Language > Your choice
      User Profiles > Your choice
    Options > Settings
    Interface > Mostly your choice
      Game Directories and Autoload Directories> games folder
    Input
      Input Device > Your controller
       (Note: Some games only work with Joycons (fuck you Boxville) in that case, set Controller Type to Dual Joycons)
      Set buttons accordingly
        (Note: Xbox controllers have no motion controls. Mods exist for games that require motion such as a shrine in BotW, search online)
    System
      System Region > Yours if you're using your own dumped games
      System Language > Your choice
      Enable Match System Time
    CPU
      Memory Manager Mode > Host
      Turbo Mode Multiplyer > 200
    Graphics
      Graphics Backend > Vulkan
      Enable Texture Recompression > Hover over and read
      Resolution Scale > Higher if you have beefy computer
      Anisotropic Filtering > Auto or 16x
    Hotkeys > Your choice
    Network
      Multiplayer Mode > RyuLDN (If you want to play multiplayer)
      Enable Guest Internet Access/LAN Mode
    Hit OK
    ```

And you've set up a switch emulator! Contact @bubble_cookies on dickcord or [open an issue in github](https://github.com/bubblecookies/bubblecookies.github.io/issues/new) if you need any help or have any suggestions.

## Enjoy!
## Roms
<details>
  <summary> Read this V first then click on this text.
</summary>
  
  https://axekin.com/  
  https://ziperto.com/  
  https://nxbrew.net/  
  https://fmhy.net/gaming#nintendo-roms
  
</details>

https://fmhy.net/beginners-guide#adblocking

## No AI used — only humans here! (emdash added for irony)
