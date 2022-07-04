# Tri-Zero/V0 Mods

This is an intial release of the CAD for my T0 Mods. Included in the CAD are the following Mods:  
- PSU Backpack
- Nema 17 Mod for 6mm belts
- Raspberry pi and RS25 mount for printed deck panel
- Zero Panel Style tophat Mounts

As of the time of writing I am releasing all of these mods in CAD form. People intending to print these mods will need to export the STL's from fusion themselves. This will be updated as time goes on. Additional documentation for each mod will be added on an ad-hoc basis. These mods are presented as is. 
The CAD presented is using Zruncho3D Tri-Zero Alpha 5 as the base. Unless specifically noted, all other mods to the V0 you see in here are created by Zruncho3D. Check out their amazing work here: https://github.com/zruncho3d
Other mods are included in the CAD provided:
- Zrunco's Zero Panels https://github.com/zruncho3d/ZeroPanels
- Hartk1213's Deck panel for the PI and RS26 mount to attach to. https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/hartk1213/Voron0_deck_panel_with_logo_and_VORON0

## PSU Backpack

The PSU backpack is designed to act as a rear door and PSU holder for an LRS200. 
Through testing I have found the hinge is very strong, and in my instance once I put a self tapping screw in to the hinge to lock the click in mechanism it is strong enough to hold the entire printer(not recommended) 
There are magnet holes in the door panel. The spacing on the magnets is such that you can use the same magnet latches used for the V0 front door.

It could be used without the PSU installed, and I have intent to do a 5015 controller cooling mod for this. Please contact me (TheMrFish#3985 on Discord) if you need this and I will make it a priority.

## Nema 17 Mod

The Nema 17 mod uses a modified AB motor mount that puts the motors on top of the mounts and has appropriate hole spacing for Nema 17 motors. This mod was inspired by a video of Berevals printer posted on discord late 2021. Inspired I made my own version which is what you will find here, credit goes to bereval for the ideas. He has since released his mod and has some great information about when and why to use this mod: https://github.com/Beraval/V0.1-Nema17-Mod

My opinions on why Nema17? Testing has found that with a good build you are for 40k accellerations and up to 900mm/s(not necessarily at the same time) with cheap OMC 17HS19-2004S1 and TMC-2209. With the big LDO 2.5a motors this might be even faster, and we have not been pushing the limits yet. I print daily at 350mm/s and 15k accel with excellent quality with this setup. It ends up being a lot cheaper than going for high end nema14 steppers, and you can do it within the thermal and current limits of the steppers and drivers without novel cooling solutions. 
Better performance without pushing the mechanical, thermal and electrical limits of your stepper drivers, and cheaper than a goodNema14 solutions. Do you need to do this to go fast on a Zero? Definitely not.
Note that I am running mine with 9mm belts. I am not releasing this with this CAD at this point, there is no good technical reason to go to 9mm. Others using the 6mm mod are getting marginally better performance than I am with 9mm. Reasons TBD, but it tells me it's probably no worth it unless you have some other specific need. Again, contact me if you need this version of the mod. 

Important notes:
- Due to size contstraints, once installed you cannot access the front two motor screws. I recommend you apply threadlocker and then tighten these front bolts down just far enough that they remove play up and down, but still allow the motor to move back and forth with some pressure for tensioning. The rear two screws can be tightened after tensioning. 
- The mod can be used with the standard top hat mounts also found in the same CAD. Standard rear tophat mounts cannot be used as the motors block access to the bolts required to secure the tophat. The mounts provided are not amazing but they work.
- This mod has been tested with 48mm motors. Longer motors will work, but there may be clearance issues with the tophat. 
- the motors sit flush with the rear tophat panel. Mods that address this will be forthcoming. So far this has not caused any issue with my tophat panel or the motors using OMC 17HS19-2004S1 1.8 degree steppers.



