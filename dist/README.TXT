==================
AUTHOR INFORMATION
==================
Written by Kenneth Robertson, STO handle @uglydisease
Suggestions: KenDaveRob@gmail.com
http://www.kenssoftware.net


==============================
ABOUT STO SKILL REVAMP PLANNER
==============================
This is a very rough alpha, but it is functional enough to allow players to try out different builds.  

If you like this program and want me to continue working on it (adding icons, tooltips, total stats, saving/loading builds etc.) let me know otherwise I will likely let this project die.

=========================
RUNNING STO SKILL PLANNER
=========================
Assuming your java run time is up to date and you have the file path to the run time files store in your operating system you should be able to simply double click on the "STOSkillPlannerRevampAlpha.jar" file.  If you have any problems you can try going to your command prompt and typing java -jar "X:\FILEPATH\STOSkillPlannerRevampAlpha.jar" where X:\FILEPATH is the location of the .jar.  Make sure you have JAVA_HOME System variable set to your java runtime if your running windows.

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "STOSkillPlannerRevampAlpha.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
