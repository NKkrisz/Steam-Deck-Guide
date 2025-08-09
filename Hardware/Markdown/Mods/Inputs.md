# Input Modifications

## Joysticks
- LCD Steam Decks have 2 different versions (revision) because [capacitive touch was changed in some way(?)](https://www.ifixit.com/Guide/Steam+Deck+Left+Thumbstick+Replacement/148896)
    - To know which one you have go to Settings -> System and check the Steam Deck Controller ID
        - MEDA - Type A
        - MHDA - Type B
    - Make sure to buy the correct replacements if necessary (3rd party joysticks might have a switch on them to work as any type)
- Make sure to calibrate after modification (replacing the modules or adding silicone ring etc...) - [iFixit Steam Deck Joystick Calibration Guide](https://www.ifixit.com/Guide/How+to+Calibrate+Steam+Deck+Thumbsticks/150415)

### Hall Effect Joysticks
- Gulikit
    - [LCD version](https://www.gulikit.com/productinfo/1026071.html)
        - This has 2 versions
            - The 1st version didn't have the cap included and required soldering on the old one from the stock stick
            - The 2nd version has the cap included, no soldering is required
    - [OLED version](https://www.gulikit.com/productinfo/1215825.html)
    - Both have issues with outer deadzone being square
- ElecGear (Only For LCD)
    - Might have issues with deadzones?
    - [Calibration issues when pressing joysticks in a certain way? (Read reviews)](https://www.amazon.com/gp/customer-reviews/R1B0UC03JGZM4?ref=pf_vv_at_pdctrvw_srp)
- [More information about the two / comparison](https://www.reddit.com/r/SteamDeck/comments/15c4ppn/comment/jwfxsxt/)
- HandheldDIY (Only For OLED)
    - [Tight (Increased rotational resistance)](https://www.handhelddiy.com/products/steam-deck-oled-tighter-hall-joystick?variant=49363761430838)
    - [Standard](https://www.handhelddiy.com/products/steam-deck-oled-tighter-hall-joystick?variant=49363761398070)
    - Joystick caps have matte surface
    - Calibration on the joystick modules
    - Quality Control not the greatest(?) (Read reviews)

### Custom Made Hall Effect / TMR Joystick (More info needed)
- Might be better solution compared to current hall effect offerings from Gulikit / Elecgear

### Joystick Cap Swap
- *Not Tested Yet - Basically OLED Joystick Caps Soldered To LCD Joystick Modules To Provide Better Grip And Look Better*
1. Buy OLED / LCD Hall Effect Sticks Depending On Witch One You Want (eg. Gulikit, sadly joystick caps only aren't available anywhere)
2. Desolder joystick caps from hall effect sticks
3. Desolder joystick caps from original sticks
4. Solder joystick caps from the hall effect stick to the original ones
5. Test if everything works correctly

#### How To Add Capacitive Touch to Non-Steam Deck Joysticks
> Capacitive touch is one wire connected to a copper plate.  
> That circular plate is glued on the top of the cap.  
> With a bit of patience you can remove it from original joystick cap and install it on any cap you want (that fits the Steam Deck, of course).  
> u/dvijetrecine

> Yes but how do you make it not look janky?  
> u/NKkrisz

> Only part that could look jank is the top of the stick.  
> The way I'd do it is get a big hole punch and rotate it till it cuts the middle part of the cap.  
> Then use the scalpel knife to go underneath and remove the top layer.  
> Dremel would be handy to smooth the bottom of the newly made hole.  
> Making a copper pad and soldering a wire is the next step.  
> After you make a hole for the wire to go through the thumb cap, use thin double sided tape to hold it in place.  
> Next step would be a bit more double sided tape and a circular plastic cover that would go over the copper pad.  
> Valve used double sided tape and plastic cover so I don't see the reason we can't do the same.  
> To keep the wire from moving around on the bottom side, it can be glued to the underside of thumb cap.  
> You can go the same - route as Valve and make a small channel for the cable.  
> I'd use soldering iron with a very small tip and about 200 °C to not melt it too fast.  
> u/dvijetrecine

[Original Comments On Reddit (It's slighly edited on this page)](https://www.reddit.com/r/SteamDeckModded/comments/1j2dgtm/comment/mfr2jgm/)

### Joystick grips
- [Playvital](https://playvital.com/collections/steam-deck-thumb-grip)
- [Skull&Co.](https://skullnco.com/collections/steam-deck/products/thumb-grip-set-for-steam-deck)

### Silicone Joystick Protector Rings
- Benefits:
    - Multiple colors available for extra customization
    - Sticks don't make noise hitting the shell
    - Stem won't have wear marks
    - Smooth movement remains
- [Playvital](https://playvital.com/collections/steam-deck-control-precision-rings)

### Xbox Elite 2 Joystick Module And Cap Swap
- [Tutorial](https://www.youtube.com/watch?v=qO3G0MXIltg)
- [Reddit Post](https://www.reddit.com/r/SteamDeckModded/comments/1bni7ro/swapped_standard_thumbstick_for_one_from_xbox/)
- Negatives:
    - Requires:
        - Desoldering stock joystick module
        - Spacers with different screws
        - Modifications to the back shell (Cutting)
    - Loses of capacitive touch
- Benefits:
    - Easily swappeable joystick caps
    - Adjustable tension for the joysticks

## Buttons

### Clicky Buttons
- [ExtremeRate Clicky Buttons (LCD & OLED)](https://extremerate.com/collections/for-steam-deck-clicky-kit)
    - [Sound and feeling can be changed to be a bit more quiet and less tactile by putting painters tape on the buttons](https://www.reddit.com/r/SteamDeckModded/comments/1hewzl7/achieving_a_quieter_tactile_buttons_dpad_w_the/)
    - ![Taped ExtremeRate Clicky Kit](../../Images/Other/JustTheEngineer_Clicky_Taped.jpeg)
- [DIY Method With Mouse Buttons (Cheaper too!)](https://www.reddit.com/r/SteamDeckModded/comments/1igzmr4/this_diy_clicky_buttons_mod_cost_me_2_bucks_but/)
    - [Video of how it sounds](https://imgur.com/a/MxtREr9)
    - Instructions:
        1. Get mouse switches (eg. Omron, Kailh)
        2. Take off flex board
        3. Scrape off coating
        4. Solder on the switches
            - Maybe put something (eg. copper sheet) behind the board for better heat transfer
        5. Shave off edges on the buttons and brackets around the buttons on the shell
    - ![DIY Clicky Buttons](../../Images/Other/Dvijetrecine_DIY_Mouse_Clicky_Buttons.webp)
    - [Another Attempt with Omron B3FS-1000P Buttons](https://www.reddit.com/r/SteamDeckModded/comments/1izgji8/yet_another_clicky_buttons_mod/)
        - ![DIY Clicky Buttons #2](../../Images/Other/Dvijetrecine_DIY_Clicky_2_Finished_ABXY.webp)

### Back Button Extensions
- [Playvital](https://playvital.com/collections/back-button-enhancement)
- [Skull&Co.](https://skullnco.com/collections/steam-deck/products/back-button-enhancement-set-for-steam-deck-4pcs)

### Trigger And Shoulder Button Extensions
- [Playvital](https://playvital.com/collections/steam-deck-triggers-extenders)

### Custom Power Button
- **Work in progress**

## Triggers
- Make sure to calibrate after modification - [iFixit Steam Deck Trigger Calibration Guide](https://www.ifixit.com/Guide/How+to+Calibrate+Steam+Deck+Triggers/150411)

### Dual Stage Triggers
- [3D printed parts + tactile switches](https://www.thingiverse.com/thing:6210987)
    - The original model only works with LCD Decks but there is a [remix available for OLEDs here](https://www.printables.com/model/1376881-dual-stage-trigger-mod-oled-version)
- Similar Feeling To Steam Controller ("click" feedback on full press)
- Shouldn't interfere with trigger input values
- [Testing video (W.I.P - Uses modified model)](https://www.youtube.com/watch?v=8woKzJrXp88)

## Other

### Shell / Touchpad Grips
- [Playvital](https://playvital.com/collections/steam-deck-controller-grip)