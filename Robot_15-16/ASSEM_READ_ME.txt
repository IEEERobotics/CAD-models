Record the assembly file names to open here. Old revisions of part files should be removed to clean up the CAD base before committed and synced to github. The format of this file is as follows:

#. 	Main assemblies. This should be the overall assembly and contain everything 		for the robot. Another CAD model in this category should be items like the 		course. 
#.#. 	First level of sub assemblies. The two main assemblies on this level should 		be the top half and the bottom half of the robot, which may be independant of 	each other.
#.#.#.	Second level of sub assemblies for the main bot and the first level of sub 		assemblies for the first level. Long story short, if you have sub assemblies 		of sub assemblies, they go here. Further sub assemblies are denoted by adding 	another decimal and number.  

The following are the assembly files within the github.
1. 	Everything.SLDASM
	Description: 
	This assembly should contain all of the assemblies and is the entire model. 

1.1.	Bottom half

1.1.1 	ChassisMod.SLDASM
	Description:
	This assembly is the lower half of the bot. This assembly should contain the 		acrylic base, the wheels and drive motors, motor mounts, batteries, and 		microstacks. This assembly should be able to drive itself and serve as a 		localization learning platform.

1.1.1.	
	Description:


1.2. 	mounting_assy_rev3.SLDASM
	Description:
	This assembly is the upper half robot assembly. The model should contain the 		hopper, the robotic arm, and everything required to complete the competition 		tasks. This assembly should have clear break points for wires, structural 		mounts, etc and it should be clear that this assembly can stand alone for 		testing. 

1.2.1. 	
	Description:
	