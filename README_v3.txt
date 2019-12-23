------------------------------------
------------------------------------

Readme file for Brownian Disks Lab (BDL)

------------------------------------
------------------------------------

REQUIREMENTS:
------------------------------------

Please, be sure that JRE (Java Runtime Environment) is installed on your computer. You can download the lastest version of the JRE for your operating system on http://www.java.com/en/download.
Also, "java" command must be accesible without indicating its complete full path. 
To check this, open a console and type "java". 
If the command is not recognized, you have to introduce it in the CLASSPATH. 

In GNU/Linux, you may change the default JRE and select at least the version 7 of Java JRE. EjsS 5.3 can produce Java and Javascript code, but it is not fully compatible with Java 9. 
Additional instructions are given in the User's Manual.

PACKAGE FILES:
-----------------------------------

The software, source code, and documentation are included in the file "BDL_files.zip", which contains the following:

1 - README.txt (this file)
2 - Brownian_disk_lab_v1.1.jar (executable)
3 - users-manual_bdl_v1.1_2019: User's Manual. It contains explanations about how to use BDL, different aspects of the underlying physics, and details regarding the developed code. 
4 - code_BDL_v1.1.zip: This zip contains the source code in EjsS, the independent java files, and the package details in javadoc format.
5 - example_read_files.zip: this zip contains a directory with an example about how to read input files in the version 1.1 of BDL.


INSTALLATION:
------------------------------------

BDL is a stand-alone application and no installation is needed. For executing the graphical users interface (GUI) you have to open to the "jars" directory and execute (double click) in the "Brownian_disk_lab_v1.1.jar" jar file (if Java is installed).  


EXECUTION
------------------------------------

See User's Manual (users-manual_bdl_v1.1_2019.pdf).


TESTING THE APPLICATION:
------------------------------------

Press the "Play" button in the "Simulation" panel which appears by default in the GUI. 
It will run a simulation during 10 seconds for 10 particles without applied forces (only in walls and to avoid overlapping). 

When finished, the data can be saved by pressing the "Write data" buttons with the disk image (see User's Manual for further instructions). 

The disks' positions will be saved in a file named "FILENAME.txt", whereas the input parameters will be saved in one named "input_FILENAME.txt". These files are stored in the user's default directory (see "Input" panel). 

To run the simulation again, press the "Refresh" button, next to the "Play/Pause" button. To liberate memory and restore the input parameters to their default values, press the "Reset" button 

Please read the User's Manual file for further details and information.







