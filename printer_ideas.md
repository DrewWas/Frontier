# The printer will be responsible for (seperately) printing the floor, frame, likely walls, and possibly roof.


* The printer may need multiple printer heads to adjust depending on material used for the piece.

* Lets design it so that it can print within a very large verticle and horizontal radius.

* Design could very well resemble a 6 armed robot (wouldnt look like a traditional 3D printer) 



## List of Pros and Cons from working with my own 3D printer (some of these are probably only specific to the one I bought)

Pros:


Cons: 
    - Way too big, the system for manouvering a xyz space is probably easier with three seperate one dimensional rods, but it makes the system so fucking big because it has to take up all the space that it can possibly print to.
    * Instead, I would rather it be a 6 (maybe more, maybe less) axis/arm robot that can telescope its own arms in or out to minimize space. The telescoping arm thing is an idea, but the 6 axis redesign is very serious. Cons with this design, as mentioned earlier - it may be harder to precisley print
    * Even crazier, we could then put this 6 arm on wheels for making very large structures, or for giving the printer more accesibilty to its environment (this means we would also have to include cameras (eyes) and hella other (difficul) software. Maybe we'll fork openpilot)

    - Way too loud. Most of this is coming from the fan on the nozzle. Maybe look into how high end computers cool their motherboards without being loud asf



    - Way too many pieces. Shit took like 2 hours to put together and there are so many unneccessary pieces. The best part is no part

    - Jams/Clogs are a TOTAL PAIN IN THE ASS. Need to take half the fucking thing apart with all these special tools and it lowkey seems dangerous. 

    - Because the nozzle has to melt the plastic, it has to get really hot, which means it draws a ton of power. We have to find a good way to efficiently draw as little power as possible while also getting the nozzle hot
    * Out of the box ideas: Make the filament not need to heat up relativley that much to melt (could cause other problems tho), use something other than heat to 'melt' the filament, somehow make the filamnet really 'meltable' to only specific conditions



    - Massive power supply. Kind of ignorant right now on how this could or could not be optimized, but immediatley sticks right out to me



    - Shitty integration. (To my understanding) I have to fucking download designs from a CAD program, THEN to a slicer program, THEN i have to download this file from the slicer program to a physical SD card, then insert this SD cart into the printer and fiddle with the printer display to print the file I want 
    * Information transmission should ALWAYS be non-physical (bluetooth). To many compiling steps. Maybe Ill write a CAD/slicer/gcode compiler

    - Bad cable management. Feel like I'm alwasys about to snap a cable. Pretty easily avoidable but I guess this problem is a symptom of being build-it-yourself



    - Manually leveling the nossle is a pain in the ass. This is a symptom of its xyz coordination being set up on 3 seperate 1 dimensional rods. Putting it on a 6 arm would definitley help in that now it only needs callibration in 1 dimension (up/down) rather than 3. This callibration may also have to be manual (prob not, but I cant think of any solutions off the dome), but would still be much easier than this shit


    - Way the printing material is wound into the nozzle looks stupid. Also makes the printer THAT much larger. Since the material is round around a cylinder, it would be cool if the base of a 6 arm printer had a small hatch in which you inserted the printing plastic and it was therefore hidden. This probably would go in the very first 'cake level' of the 6 arm because the base needs to be the heaviest part (low center of mass) so would therefore house batteries/power supply, but still throwing it in one of the 'cake levels' would be a nice way to hide it


 *** A large problem I immediatley notice is that 80% or more of the space the printer takes up is dedicated to moving around the nozzle. Similarly, the number of parts and likely electricity follows this distribution. This is an issue. <u>How do we minimize size and electricity that is not fed to nozzle</u>***

  -- Still however, this issues regarding the printer are not end all be all. Just casual observations that must be addressed when we build our own, however a clean, thorough, and rubust design is absoluty essential for structure design. As we will likely only build on the order of 10s of printers, but hopefully millions of structures


## Filament

    - Carbon Fibre??


