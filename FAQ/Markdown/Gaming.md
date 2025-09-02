# Gaming On The Steam Deck

## Buying Games
- [Top played games on Deck](https://store.steampowered.com/charts/steamdecktopplayed)
- [Steam](https://store.steampowered.com/)
    - [Steam Sales Calendar](https://steamdb.info/sales/history/)
- [Fanatical](https://www.fanatical.com/en/)
- [Humble Bundle](https://www.humblebundle.com/)

## Game Compatibility
- [Steam Deck Compatibility Program](https://www.steamdeck.com/en/verified)
- [ProtonDB](https://www.protondb.com/)
- [SteamDeckHQ](https://steamdeckhq.com/)
- [ShareDeck](https://sharedeck.games/)
- YouTube
- Reddit
    - [r/SteamDeck](https://www.reddit.com/r/SteamDeck/)

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
- [XBPlay](https://store.steampowered.com/app/2693120/XBPlay/) - Stream One and Series S/X consoles in 1080p 
- [Chiaki-ng](https://streetpea.github.io/chiaki-ng/) - PlayStation Remote Play for Everyone
- [Sunshine](https://github.com/LizardByte/Sunshine) & [Moonlight](https://moonlight-stream.org/) - PC Streaming

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

### Battery
- Shows battery level in %
- Calculates remaining battery life in hours and minutes based on current power usage

### Performance Overlay Level
- Off: No overlay 
- 1: FPS only in top left corner
- 2: FPS, Frametime, CPU, GPU, RAM, VRAM, Battery, Power Usage and Time information in a row at the top of the screen
- 3: Same as level 2 but a tiny bit more detailed and on the left side
- 4: Everything on the left side

**To use settings below you need to be in ```Advanced View``` instead of ```Basic View```**

### Performance Settings

#### Use per-game profile
- Toggle to use saved Performance Settings for currently running game

#### Frame Limit
- Sets framerate and display refresh rate limit
    - Optimal settings:
        - LCD (60hz screen): 30 / 40 / 60
        - OLED (90hz screen): 30 / 45 / 90

#### Disable Frame Limit
- Allows the Deck to go beyond the highest frame limit

#### Allow Tearing
- By default the Deck uses some form of sync so there isn't tearing on the screen making the image smoother with the downside of more input lag
- [Currently this option doesn't seem to work](https://github.com/ValveSoftware/SteamOS/issues/1391)

#### Half Rate Shading

#### TDP Limit
- Limit power usage - can be useful to extend battery life in exchange for less performance

#### Manual GPU Clock
- In certain situations it's more beneficial to set this manually

#### Scaling Mode
- Auto:
- Integer:
- Fit:
- Stretch:
- Fill:

#### Scaling Filter
- Linear:
- Pixel:
- Sharp:

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