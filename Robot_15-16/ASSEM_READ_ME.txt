Record the assembly file names to open here. Old revisions of part files should be removed to clean up the CAD base before committed and synced to github. The format of this file is as follows:

#. 	Main assemblies. This should be the overall assembly and contain everything 		for the robot. Another CAD model in this category should be items like the 		course. 
#.#. 	First level of sub assemblies. The two main assemblies on this level should 		be the top half and the bottom half of the robot, which may be independant of 	each other.
#.#.#.	Second level of sub assemblies for the main bot and the first level of sub 		assemblies for the first level. Long story short, if you have sub assemblies 		of sub assemblies, they go here. Further sub assemblies are denoted by adding 	another decimal and number.  

The following are the assembly files within the github.
1. 	Everything.SLDASM
	Description: 
	This assembly should contain all of the assemblies and is the entire model. 

1.1.	bottomHalf.SLDASM
	Description:
	This assembly contains all part files for the lower half of the bot.

1.1.1. 	ChassisMod.SLDASM
	Description:
	This assembly is the lower half of the bot. This assembly should contain the 		acrylic base, the wheels and drive motors, motor mounts, batteries, and 		microstacks. This assembly should be able to drive itself and serve as a 		localization learning platform.

1.1.1.1.MotorWheelAssy.SLDASM
	Description:
	This assembly contains the motor mount, the wheel, the shaft coupler, and the 	motor used in the drive train as is. 

1.1.2.	stack.SLDASM
	Description:
	This assembly contains the entire microstack model and the approximated board 	spacing. It contains the worst case scenario situation in the event that all 		six boards need to be used. 

1.2. 	mounting_assy_rev3.SLDASM
	Description:
	This assembly is the upper half robot assembly. The model should contain the 		hopper, the robotic arm, and everything required to complete the competition 		tasks. This assembly should have clear break points for wires, structural 		mounts, etc and it should be clear that this assembly can stand alone for 		testing. 

1.2.1. 	Robotic Arm.SLDASM
	Description:
	This assembly contains the robotic arm as pulled from GrabCAD. It is advised 	not to open this assembly unless a reorientation of the arm is required. 

1.2.2.	holder_sub_rev2.SLDASM
	Description:
	This assembly contains the entire upper arm holder used to move the arm 	around the upper robot. 