ant-jmeter
==========

JMeter Ant Task - An Ant task for running JMeter test plans.


Build Requirements:
===================
You need the following:

1. The latest version of Eclipse
2. The latest build of the Ant.jar file

For OSX, you can install Ant by downloading and installing ant from homebrew. 
Ant.jar will be found in /usr/local/Cellar/ant/<version>/libexec/lib/Ant.jar

Building:
=========
Update the classpath (if needed) in Eclipse for the "Ant.jar"

1. Right-click the project --> Build Path --> Configure Build Path...
2. Under the "Java Build Path" section, click on "Libraries.
3. Remove the current ant.jar library.
4. Click on "Add External JARs..." and search to add your ant.jar
5. Click OK when finished and run a build

Export JAR:
===========
1. Right-click the project and click on "Export..."
2. Expand "Java" and click on "JAR file". Click Next >
3. Uncheck all the "Select resources to export" items at the top
4. Make sure "Compress the contents of the JAR file" is checked
5. Select your export destionation and click "Finish"
