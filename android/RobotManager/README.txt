Google Glass Driver Demo

This code is a modified version of the RobotManager google glass application (https://github.com/RIVeR-Lab/google_glass_driver).

It does not require the user to connect to a bluetooth device or register any robots.

It initializes with two robots, Anna and Oryx. It also includes a message from each 
of the robots.

The available voice commands are:

"All robots"
"Start listening"
"Stop listening"
"Close robot manager"
"View robots"
"View messages"

To set the focus to a particular robot, simply say its name. (Note: will not work 
if a multi-part command has started to be given, shown by an underscore character)

When all robots are in focus, all of the commands available to each robot are available.
When a single robot is in focus, only its commands and the above listed commands are
available.

Robot commands: Note - Commands with options have the options listed in tabs.

Anna's commands:
Stop
Drive
	Forward
		Slowly
		Quickly
	Backward
		Slowly
		Quickly
Turn
	Left
		Slowly
		Quickly
	Right
		Slowly
		Quickly
Save location
	kitchen
	bathroom
	bedroom
	front door
Go to
	kitchen
		Slowly
		Quickly
	bathroom
		Slowly
		Quickly
	bedroom
		Slowly
		Quickly
	front door
		Slowly
		Quickly
		
Oryx's commands:
drive
	forward
	backward
turn left
turn right
look up
look down
look left
look right
move arm up
move arm down
move arm left
move arm right
save location
	home
	sample
	checkpoint
go to
	home
	sample
	checkpoint
again