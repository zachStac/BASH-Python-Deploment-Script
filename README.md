# BASH-Python-Deploment-Script
Goal: I recently have had to deploy python3 and a list of add-ons to several Linux systems. Most of this is to be a form of a template that can be molded to fit the needs of the OS types, and any libraries or packages that are needed on a Linux system. This script can be used to install just python3 (version is based on needs at the time of deployment). The script can also install any extras, or it can remove python and its extras.

To Do:  
	Build a script that can install python on Linux systems. 
	Add an ability to select options form a CMD.
	Add an ability to remove python
	Add an ability to install python libraries and extras 
	Add an integrity check on user input 
	Work on speed and efficiency of the script
	Attempt to fuzz the script for fun, learn about fuzzing 
	Fine toon the CMD view, for ease of use
	Add notes to the script and make small adjustments 

Project: 
•	Current version of the script has been built for Ubuntu using apt, for other Linux systems apt may need to be replayed with other package mangers. Current the script is directed to the bin/bash/, this may need to be changes in some special cases. VERSION 1
•	Added the addition of a set of if/ elif statements. Each statement has a one or two 
Roles, for example installing python or deleting python. Some of the statements will need to be changed and adjusted for efficiency. Statements also need the addition of pauses and checks to ensure that all the installs ad process went through correctly. VERSION 1


