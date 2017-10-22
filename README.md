# TicTacToe
This is a game of the famous TicTacToe which can be played with an AI or your friend

Setup 
-----

Environment variables
Go to Control Panel\System and Security\System
Next is Advanced system settings --> Go to Advanced tab --> Environment Variables
Basically its setting your classpath so that you can execute your Java code from anywhere.

Add the following three variables and values :

JAVA_HOME
C:\Program Files\Java\jdk1.8.0_51\bin

JRE_HOME
C:\Program Files\Java\jre1.8.0_131

CATALINA_HOME
Your apache extract folder\apache-tomcat-9.0.1

And there will be a path variable. Add this line.

%CATALINA_HOME%\bin


You are done setting up, I promise.

Extract the apache-tomcat-9.0.1.

Open http://localhost:8080/Game/ in your browser.
