# Moose trappers 3000 BC Lappland Sweden

## WHAT IS IT?
A simulation of hunter gatherer household dependence on moose migration pattern and the impact of wolves and bears in the area. The moose are trapped with pitfalls or other device, which can be placed at strategic places. Plots shows how many moose are killed by predeators and household. Moose also die naturally at the age of 15. Moose and predators can reluctantly swim across water. Households have no problem crossing water.
## WHERE IS IT?
Two areas can be chosen for the simulation, Stalon or Gråtanån. These areas are located near Vilhelmina in Västerbotten county, Sweden. The assumed hunting territories for each household have borders based on the watershed, marked with dotted lines (Stalon) or colored green (Gråtanån).
## WHAT DO THE BUTTONS DO?
### TERRITORY
Choose one of the two alternative territories **Stalon** or **Gråtanån**.
Each area has a corresponding map drawing that does not affect the simulation. The terrain map (DEM) underneath the drawing, is assigned to the patches and are important for the simulation of moose migration. The maps dimensions are 43 x 43 km. Each patch is 100x100 meter.
### NUMBER OF MOOSE
Choose a number of moose to start with. Age, sex, preferred summer home and individual length of migration is set randomly.
### RESET – PRESS TWICE
Moose winter and five summer home areas are placed randomly. Their locations can be changed with the **move agents button**. Four camps are created, one for each season. Their default placement corresponds to archaeological data, but can be moved elsewhere as all other agents.
### MOVE AGENTS
When the button is active the camps, moose winter/summer areas, and other agents can be moved.
### ADD TRAPS/PITFALLS
Traps (pitfalls or other device with fences between) can be added and are active when the household is nearby.  When button is pressed a target symbol appears on the map. Move the traps to desired location.
### ADD WOLF PACK
When button is pressed a wolf apears on the map. The wolf symbolizes a wolf pack and hunts moose calves and old female moose.
### ADD BEARS
When button is pressed a bear apears on the map. The bear only kill moose calves in the spring and during winter (nov-april) the bear is hibernating.
### HIDE/SHOW LABELS
Displays the seasonal distinations for household and moose
### DRAW TRAJECTORIES
Draws a line showing the movement of moose and houshold
### IMPORT/EXPORT PRESETS
The current set can be saved with **export presets** and loaded with **import presets.**
Note that if you want to save several sets you can use **export/import-world _filename_** in the menu. If chosen territory does not match the preset, an error appears.
### MOOSE SPEED / WALK / PREDATOR-SPEED
The daily movement for moose, household and predators respectively. One unit is 100 meter. Note that each moose also has an individual parameter <2 that's added to the speed. 
###  TRAP/KILL RADIUS
If a moose and the hunter gatherer household are within trap-radius at the same time, the moose is killed. If a moose younger than 2 years old or a female moose older than 11, are within wolf-radius, the moose is killed.
Set radius according to required anual harvest. 
### JULIAN DAY
The day when households and moose start mooving to new areas/camps. Dates are chosen according to the Julian calendar, day of the year.
![](file:JulianDays.png)
## WHAT DO THE PLOTS SHOW
Three plots monitors the moose population. The bottom plot shows the number of moose within each age group.

The button **Track 5 moose** draws the trails for a random moose corresponding to each summer range, and the plot **Distance to winter home range** displays the distance each moose accomplish.
## THINGS TO TRY
Place camps and traps so that moose and household are at the same place simultaneously. Adjust the trap radius so that the household manages to trap a sufficient amount of moose.  Add predetors to see if the moose population sustains.

Many variables can be adjusted in the code, e.g. **set view-angle, view-distance** and **factor-valley** that affects moose preference to follow low altitudes and avoid lakes.

Choose other areas to analyze by ading other maps, one DEM map with blue water and a corresponding map drawing. Load you own maps with **File - Import Patch Colors - _filename_** for DEM-maps, and **File - Import Drawing - _filename_** for the map to display.
## HOW TO CITE
Lars Göran Spång, Wiebke Neumann, David Loeffler & Göran Ericsson 
The Moose Trappers and Hunting Grounds of Vilhelmina
ABM-simulation of annual cycles during the Stone Age 
Current Swedish Archaeology
https://publicera.kb.se/csa/issue/view/3061

NetLogo and the routine **build**
Wilensky, U. (1999). NetLogo. http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
