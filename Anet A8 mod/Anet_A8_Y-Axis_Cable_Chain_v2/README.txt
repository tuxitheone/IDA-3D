                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:1915486
Anet A8 Y-Axis Cable Chain v2 by papinist is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

After printing the great cable chain designed by sukhoi27, I feel the need to do some tweak and mod to it.
- first of all, I modified the frame mount: I removed the part that goes between the frame and the nut. You don't need this level of strenght and you save a lot of time without removing the nut. I also removed the internal parts so you don't need to insert wires through it, and you can always remove the part without disconnecting all the wires.
- then I modified the hotbed mount: the original part was too tall and since you need the hotbed to be higher of that (so you won't risk the hotend to hit it when going home), you were losing 5-6 mm in height. I moved the chain part at the very bottom and cut the upper part, saving about 3 mm. Now you lose only 2 mm from the original A8 height.
- I also enlarged a bit the hotbed mount holes: now they are 4mm diameter, perfect for the cart screws.

See in motion: https://www.youtube.com/watch?v=iGdTLbeOBw0

-----------------------------------------------------
Check out all my Anet A8 projects:
- Anet A8 Prusa i3 Simple filament guide (Horizontal) http://www.thingiverse.com/thing:1764285
- Anet A8 RPi Camera Bed mount http://www.thingiverse.com/thing:1867549
- Anet A8 Y Axis Cable Chain v2 http://www.thingiverse.com/thing:1915486
- Anet A8 hotbed thermal insulation http://www.thingiverse.com/thing:1917197
- Anet A8 Power supply cover w\LCD power meter http://www.thingiverse.com/thing:2087761
- Anet A8 Z-Axis RPi Camera mount for panning timelapses http://www.thingiverse.com/thing:2265949
- Anet A8 LED Illumination MOD http://www.thingiverse.com/thing:2285674
- The One - Anet A8 - Universal Spool Holder https://www.thingiverse.com/thing:2456038
- Anet A8 Easy Magnetic Extruder Access Mod (8x2 magnets) https://www.thingiverse.com/thing:3512382

-----------------------------------------------------

# Print Settings

Printer: Anet A8 (Prusa i3)
Rafts: No
Supports: Yes
Resolution: 0.2 mm
Infill: 20%

Notes: 
- You can use brim with the mount since it has a thin base. You also need support with it.
- Print 4x "chain_x4" since you need 14 chain links. Keep some spare in case you break one of them when assembling.
- I used PLA (yellow) and ABS (blue). Apart cosmetic function, I purposedly print the hotbed mount in ABS since it's very near to the hotbed and when it reaches high temp the mount could soften and bend if it is made of PLA.

# Post-Printing

## Assembling

- Connect all the chain links
- Remove the hotbed, then remove the 3 screws on the lower cart. Place the hotbed support and screw it back. You need longer screws here.
- Insert wires in the hotbed mount, through the chain, connect the chain to the hotbed mount and route the wires toward the back of the printer.
- Install the frame mount removing the two screws on the frame and then putting them back. You don't need longer screws here. Pay attention to the wires under the mount, to not pinch them between the mount and the frame.
- Now reinstall the hotbed TURNING IT 90° ANTI-CLOCKWISE so to have the wires connector on the left, going exactly inside the hotbed mount. Luckily this printer has a square hotbed :) Reinstall the connector before putting it in place, and then screw it back.
- When all is in place, you need to cut the white lip on the hotbed connector, because it protrudes some mm up and it could interfere with the extruder when going home. Don't worry, the connector won't disconnect itself when inside the mount :)
- Route the wires on the left, under the frame to the main board and reconnect them.

Remember, you need to do the leveling procedure again.


![Alt text](https://cdn.thingiverse.com/assets/c4/22/8f/d8/45/IMG_20161112_164207_Medium.jpg)
Chain and frame mount (this mount is the older version)

![Alt text](https://cdn.thingiverse.com/assets/d9/70/61/fb/95/IMG_20161112_160624_Medium.jpg)
You need longer screws for hotbed mount

![Alt text](https://cdn.thingiverse.com/assets/6e/24/f5/e4/4a/IMG_20161122_220306_Medium.jpg)
Height comparison between original and v2 hotbed mount - I cut the 'bridge' part to mount it without removing all the wires

![Alt text](https://cdn.thingiverse.com/assets/92/a6/f3/6b/34/IMG_20161112_192711_Medium.jpg)
Cut this lip...

![Alt text](https://cdn.thingiverse.com/assets/ec/1c/2f/bf/d7/IMG_20161112_192726_Medium.jpg)
...so the connector sits flush with the hotbed

![Alt text](https://cdn.thingiverse.com/assets/ef/bb/15/69/0e/IMG_20161122_222248_Medium.jpg)
Pay attention to not pinch the wires when routing them under the frame mount

![Alt text](https://cdn.thingiverse.com/assets/b0/55/f8/7b/b7/IMG_20161114_215543_Medium.jpg)
This is how much you needed to raise the hotbed with the original mount...

![Alt text](https://cdn.thingiverse.com/assets/8e/43/00/03/24/IMG_20161122_230301_Medium.jpg)
...and this is with my new v2 mount (you can also see the insulation, see custom section below)

<iframe src="//www.youtube.com/embed/iGdTLbeOBw0" frameborder="0" allowfullscreen></iframe>
Cable chain in motion :)

# How I Designed This

Modified in Autodesk 123D Design

# Custom Section

## Hotbed thermal insulation

While you have your hotbed removed, why not take advantage and thermal insulate it?
Your heating times will be reduced and temperature during prints will be more steady.
I published my simple solution here http://www.thingiverse.com/thing:1917197

![Alt text](https://cdn.thingiverse.com/assets/66/3e/89/f0/d2/IMG_20161122_215701_Medium.jpg)