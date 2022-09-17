# Voron_v1.6.3 'Dark Lake'

Updates the Voron v1.6 branch to bring it in line with generation v1.8 build ethos. The key difference is that v1.6 generation printers utilise linear rods for guides rather than linear rails.

Updated the v1.6.2 to v1.6.3 'Darklake'. Aesthetic of printed parts has been altered to better suit the design language of the Stealthburner toolhead.

v1.6.3 supports build plates from 200x200mm. Theoretically, the design allows for build plates from 150x150mm, however this is as yet physically untested. The z_motor_mounts are slightly narrower to allow placement between the z_shaft_retainers on the smallest build size. Bottom skirts have been updated with custom 'middle' skirts for the different build sizes. 

v1.6.3 features re-designed x-carriages to support Afterburner and Stealthburner toolheads. Modified parts include carriage frames, printhead mounts and belt clips. The carriage frames are compatible with both LM8LUU bearings and their 8x15x40 bushing equivalents. Please note, although carriage frames will fit v1.6, the belt path is consistent with v1.8 and therefore not compatible without modification. Stealthburner will require the modified motor_plate_NH_DL to ensure clearances to xy_joints and full coverage of the x-axis of the bed. The connector cover (also referred to as the 'hood') has been modified to allow alternative mounting points.

XY joints are completely redesigned to bring belt path alignment consistent with v1.8 AB drives. Y_axis currently runs on 8x12x8 bushings (which are time consuming to align, but offer near silent operation), but development of LM8LUU bearings is being considered. v1.6.3 Front Idlers are adapted from v2.4r2 and also utilised in the v1.8.2 release. XY Joints have been updated to more accurate idler placements.

AB_driveframes now allow for wiring loom pass-through either side of the printer.

Y-Endstops and Y-Axis are specific to v1.6.3 (rods), but a snap-in design means that porting the printer to v1.8.2 (rails) only requires stripping and rebuilding of the gantry.

Z_bearing_blocks are interchangeable with v1.8 Testing continues with LM8UU (short bearings) and 8x12x8 phosphor-bronze/ self-lubricating bushings. Phosphor-bronze is extremely quiet, but may be less horizontally stable across the bed than their bearing alternatives in this application.

Controller board mounts for Fly Mini v1, TwoTrees E3 DIP, Ramps 1.4 and Raspberry Pi Zero are included under the 'Unsupported Controllers' directory. 

Panel mounting for 3mm acrylic panels is styled sympathetically to the bottom skirt 'honeycomb' aesthetic. Low profile snap clips are utilised for securing the front panel and rear electronics door.

Build guides for v1.6.3 and v1.8.2 printers are in-progress. 

![IMG_20210215_123016 (Large)](https://user-images.githubusercontent.com/80538348/112975809-fdb4ee80-914b-11eb-9690-1dd94bd08723.jpg)

![IMG_20210201_132335 (Large)](https://user-images.githubusercontent.com/80538348/113149652-28c23f80-922b-11eb-9908-027cbe79a90c.jpg)

