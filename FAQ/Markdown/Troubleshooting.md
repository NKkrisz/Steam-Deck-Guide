# Troubleshooting

## General
- Restart software, hardware or the Steam Deck itself
- Make sure OS / drivers / software (game) are fully updated
- Search for the issue (YouTube, Steam Deck communities etc...)
- Post about the issue you're encountering if you couldn't fix a solution
- Factory reset / reinstall OS
- [Contact Steam Support](https://help.steampowered.com/en/)
    - [Help With Steam Deck](https://help.steampowered.com/en/wizard/HelpWithSteamDeck)

## Accessing Menus And Resetting Things
**Make sure the Steam Deck is fully turned off before trying these!**

- **Force Shut Down**: Hold Power Button For 5 Seconds
- **Force Shutdown Then Restart**: Hold Power Button For 10 Seconds
- **Boot Manager**: Hold Volume(-) + Press Power Button:
- **BIOS Menu**: Hold Volume(+) + Press Power Button
- **Reset Firmware** And BIOS: Hold Volume(-) + Hold Three Dots (•••) + Press Power button
- **SteamOS Menu**: Hold Three Dots (•••) + Press Power Button

[More Information](https://www.reddit.com/r/SteamDeck/comments/17f7v8g/easy_factory_reset_option_that_valve_doesnt_want/)

## Charging
- Use stock charger or equivalent / stronger - 45W+ with USB PD support
- Avoid using magnetic chargers or cable extenders if possible

## Docking / Using A Hub
- Re-connect the Dock / Hub
- Sometimes power is needed for functionality - use a good power supply
- Try different cables if there are issues connecting a device to the dock / hub
- Update firmware of dock / hub if possible

## Gaming
- Unable to install a game due to grayed out ```Install``` button and ```Available For Windows``` text:
    - Go into the game properties' (Menu Button / Gear > Properties > Compatibility) and enable ```Force the use of a specific Steam Play compatibility tool``` (eg. Proton Experimental)
- Not all games have Steam Cloud functionality so saves need to be transferred manually between devices (eg. Dark Souls III)
- See if ```Quick Settings``` are properly configured
    - Turn off HDR if random colors appear
- See potentially limiting factors by enabling ```Performance Overlay``` in ```Quick Settings```
- Try different configurations (eg. in game settings, other Proton versions) - see [ProtonDB](https://www.protondb.com/) user reports
    - Various compatibility layers (eg. ```Proton-GE```) can be easily installed using ```ProtonUp-QT``` from ```Discover``` in ```Desktop Mode```
        - After installing them, they can be selected within the game properties' (Menu Button / Gear > Properties > Compatibility)
    - If cutscenes aren't working (only showing SMPTE color bars) try ```Proton-GE```

## Controls

### Joysticks
- [Recalibrate with ```Konsole``` in desktop mode using ```thumbstick_cal```](https://www.ifixit.com/Guide/How+to+Calibrate+Steam+Deck+Thumbsticks/150415)

### Triggers
- [Recalibrate with ```Konsole``` in desktop mode using ```trigger_cal```](https://www.ifixit.com/Guide/How+to+Calibrate+Steam+Deck+Triggers/150411)

## Accessories & Bluetooth
- If it's a Bluetooth device sometimes re-pairing it can help to connect it again
- Xbox Wireless controllers might need a [firmware update](https://support.xbox.com/en-US/help/hardware-network/controller/update-xbox-wireless-controller) to connect properly
- MicroSD cards can be faked, buy from reputable sellers that have good return / refund policy

## Decky
- Disable it and update / reinstall / uninstall in Desktop Mode