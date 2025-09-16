# Gaming On The Steam Deck

## Buying Games
- [Top played games on Deck](https://store.steampowered.com/charts/steamdecktopplayed)
- [Steam](https://store.steampowered.com/)
    - [Steam Sales Calendar](https://steamdb.info/sales/history/)
- [Fanatical](https://www.fanatical.com/en/)
- [Humble Bundle](https://www.humblebundle.com/)

## Game Compatibility
- [Official Steam Deck Compatibility Program](https://www.steamdeck.com/en/verified)
- [ProtonDB - Welcome to your home for crowdsourced Linux and Steam Deck game compatibility reports!](https://www.protondb.com/)
- [Are We Anti-Cheat Yet? - A comprehensive and crowd-sourced list of games using anti-cheats and their compatibility with GNU/Linux or Wine/Proton.](https://areweanticheatyet.com/)
- [SteamDeckHQ - News, Reviews, Articles, Videos, etc...](https://steamdeckhq.com/)
- [ShareDeck -  An unofficial site to find and share Steam Deck performance configurations.](https://sharedeck.games/)
- YouTube
- Reddit
    - [r/SteamDeck - The Unofficial Subreddit for the Valve Steam Deck! Find discussions, games running on Deck, hardware / software mods and much more!](https://www.reddit.com/r/SteamDeck/)

## Game Launchers & Other Stores
- Discover - The default software center in ```SteamOS``` found in ```Desktop Mode```
- [Prism Launcher](https://prismlauncher.org/) - Vanilla & Modded Minecraft
- [Heroic Games Launcher](https://heroicgameslauncher.com/)
- [Lutris](https://lutris.net/)
- [NonSteamLaunchers](https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck)
- [Junk Store](https://www.junkstore.xyz/)

## Emulation
- [EmuDeck](https://www.emudeck.com/)
- [RetroDeck](http://retrodeck.net/)

## Remote Play
- [Steam Remote Play](https://store.steampowered.com/streaming/)
- ~~[XBPlay](https://store.steampowered.com/app/2693120/XBPlay/) - Stream One and Series S/X consoles in 1080p~~ - [Support Ended](https://store.steampowered.com/news/app/2693120/view/553501640235156546)
- [Greenlight](https://github.com/unknownskl/greenlight) - Greenlight is an open-source client for xCloud and Xbox home streaming made in Typescript.
- [XStreamingDesktop](https://github.com/Geocld/XStreamingDesktop) - XStreaming is an open-source mobile client for xCloud and Xbox home streaming, greatly inspired by Greenlight.
- [Chiaki-ng](https://github.com/streetpea/chiaki-ng) - Next-Generation of Chiaki (the open-source remote play client for PlayStation)
- [Moonlight-qt](https://github.com/moonlight-stream/moonlight-qt) - Moonlight PC is an open source PC client for NVIDIA GameStream and Sunshine.
- [Sunshine](https://github.com/LizardByte/Sunshine) - Self-hosted game stream host for Moonlight.

## Cloud Gaming
- [Xbox Cloud Gaming in Microsoft Edge](https://support.microsoft.com/en-us/topic/xbox-cloud-gaming-in-microsoft-edge-with-steam-deck-43dd011b-0ce8-4810-8302-965be6d53296)
- [Nvidia Geforce Now App](https://www.nvidia.com/en-us/geforce-now/download/)
- PlayStation Plus - Requires tinkering with Proton or easy install with [NonSteamLaunchers](https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck)

## Quick Settings

### Brightness Slider / HDR
- For HDR to work on compatible displays (eg. OLED Steam Deck internal screen) these are the requirements:
    - Play in Gaming Mode (HDR only works on Wayland, Desktop Mode uses X11)
    - Game supports HDR and is enabled in the settings
    - Game is set to fullscreen mode
    - Helpful commands:
        - For some games that run outside of the Steam library - ```DXVK_HDR=1 PROTON_ENABLE_AMD_AGS=1 %command%```
        - For certain games ```SteamDeck=0 %command%``` and ```-dx12``` or ```-d3d12```
- Some information here is copied from and additional useful things [can be in this guide by u/mytrixx on r/SteamDeck regarding HDR](https://www.reddit.com/r/SteamDeck/comments/1868qyv/steam_deck_oled_hdr_games_guide/)
- Two-tone slider explanation:
    - First part adjusts the brightness via the display hardware which changes how strongly each pixel lights up.
    - Second half adjusts the brightness via digital gain on the image we send to the display.
    - Source: Valve Employee - Slightly edited for better grammar / punctuation

### Audio

#### Volume & Microphone
- Mute or set loudness of your current output device and microphone

### Other

#### Airplane mode, Wi-Fi, Bluetooth, Night mode
- Toggle features
- Bluetooth ```Add Device``` button navigates into ```Settings > Bluetooth```

### Controller

#### Game rumble

#### Steam haptics

## Performance
- There is built in additional information for the options below, use the button shown on the bottom of the screen to view them
    - Information written in style ```like this``` is copied from there

### Battery
- Shows battery level %
- Calculates remaining battery life or charging time in hours and minutes based on current power consumption

### Performance Overlay Level
- ```Adjust this setting to control how much data is shown in the performance overlay.```
- ```The performance overlay provides realtime data about the current status of your device, including frames per second, power consumption, GPU and CPU usage and more. This data can be useful to determine how a settings change impacts performance and battery life.```
- Off: No overlay
- 1: FPS only in top left corner
- 2: FPS, Frametime, CPU, GPU, RAM, VRAM, Battery %, Power Consumption and Remaining Time / Charging Status information in a row at the top of the screen
- 3: Level 2 but a bit more detailed and on the top left corner
- 4: Everything on the left side (too long to list)

**To use settings below you need to be in ```Advanced View``` instead of ```Basic View```**

### Performance Settings

#### Use per-game profile
- Toggle to use saved Performance Settings for currently running game

#### Frame Limit
- ```Specify the maximum frames per second (FPS) the game is allowed to render. Users typically prefer framerate limits near (or slightly lower than) the game's average framerate.```
- ```Higher framerates typically produce smoother / lower-latency gameplay, at the expense of increased power usage.```
- ```Some games may have adverse effects when refresh rate limiting is enabled, including increased input lag or audio glitches. For these cases it is recommended to set the framerate limit to the maximum.```
- Optimal settings:
    - LCD (60hz screen): 30 / 40 / 60
    - OLED (90hz screen): 30 / 45 / 90
- In the beginning there were separate sliders for framerate limit and refresh rate
    - This then got replaced by the current implementation called ```Unified Refresh Rate Management``` and it was toggleable in ```Display``` settings until the option got removed

#### Disable Frame Limit
- ```Disabling the frame limit allows games to render as fast as hardware performance allows (potentially higher than the display refresh rate).```
- ```This setting may minimize frame latency for some games, but can potentially consume large amounts of power to render frames that will not reach the screen.```
- ```It is recommended to keep this settings disabled under normal usage to preserve battery life.```

#### Allow Tearing
- ```This toggle allows a game to render at a different refresh rate than the display.```
- ```Synchronizing the game's render output with the display can introduce latency to the render pipeline. Enabling this setting can mitigate this latency, but can result in tearing artifacts during gameplay.```
- ```To take advantage of this setting, VSync must be disabled in the game's settings and the frame limit setting must be turned off.```
- [Currently this option doesn't seem to work](https://github.com/ValveSoftware/SteamOS/issues/1391)

#### Half Rate Shading
- ```Turning on half rate shading forcibly reduces the shading quality used by a game.```
- ```This can improve battery life and performance by reducing the amount of work a game needs to do to generate a new frame. This results in reduced visual quality for games.```
- Sometimes causes visual issues like text being less readable
- It's recommended to disable this setting the first time playing a game to avoid troubleshooting

#### TDP Limit
- ```Adjust this value to limit the maximum amount of power Steam Deck is allowed to consume.```
- ```Lowering the TDP limit reduces the amount of work the system is allowed to do per second. This results in improved battery life, bu will also reduce the system's performance while playing games.```

#### Manual GPU Clock
- ```Adjust this value to set a fixed clock for the system's GPU, which can be useful for stabilizing a game's framerate.```
- ```Normally the GPU automatically adjusts clock frequency to balance battery consumption and performance. Some games have drastic transitions between low and high GPU usage, which sometimes hitch if the GPU does not ramp up the clocks fast enough. For these cases it can be useful to set a fixed clock to avoid a hitch due to an underclocked GPU.```

#### Scaling Mode
- ```Change this value to modify how windows smaller than the current screen resolution get scaled to fit the screen.```
- ```Auto: Preserves aspect ratio, scales up to 2x```
- ```Integer: Preserves pixel ratio (best for pixel art games)```
- ```Fill: Fill the whole display, preserving aspect ratio (will result in clipping)```
- ```Stretch: Fill the whole display without preserving aspect ratio```
- ```Fit: Preserves aspect ratio, scales up to fit the display```

#### Scaling Filter
- ```Change this value to set the post processing filter applied when an application window is scaled:```
- ```Linear: Linear interpolation filter```
- ```Pixel: Band limited nearest neighbour filter```
- ```Sharp: Platform-specific super-resolution sharpening filter```
    - Uses FSR in the Steam Deck's case

#### Show Perf Overlay In Steam
- Enables the performance overlay to show up when not playing a game in gaming mode (browsing menus)

#### Reset to Default
- Resets settings to their default value

## Maximizing Battery Life / Performance
- Use in-game settings
    - Set graphics quality
    - Set resolution
        - Use FSR / XeSS upscaling / frame-generation
- Set Frame Limit, TDP Limit and Manual GPU Clock in Quick Settings
- Set Scaling Mode and Filter in Quick Settings
- Overclock / undervolt in the BIOS

## Steam Input / Controller Templates
- Useful when there's no controller support in a software (game)
- Map various keys, buttons, use gyro, capacitive touch, trackpads etc...
- Adjust sensitivity, use different modes and layers, add menus etc...
- Back buttons, gyro, capacitive touch and trackpads aren't mapped to anything usually
    - FPS games can greatly benefit from trackpad + gyro control
    - Back buttons can be useful when multiple buttons need to be pressed at the same time / in quick succession
- Game developers and the Steam community can make templates to try out instead of making one yourself