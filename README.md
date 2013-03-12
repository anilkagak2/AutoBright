# AutoBright


## Steps to run the program

### PREREQUISITES:
+ PyQt4
+ dbus
+ Python

### Instructions
+ Double Click on the AutoBright.py file. If this doesn't run try
	python AutoBright.py
+ Set the screen brightness (if current is not appropriate for you)
by adjusting the sliding bar & click on set for applying the changes.
+ Minimize the application (currently it's not running as a service),
so that it continues to run in the background & hence able to adjust
the screen brightness automatically.

### NOTE
SOFTWARE CURRENTLY WORKING ON UBUNTU 12.10 AND GREATER


## KNOWN BUGS

+ Termination of the program through GUI is not enough. The pythod thread
needs to be killed through the terminal
