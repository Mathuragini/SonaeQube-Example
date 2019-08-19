# SonarQube-Example
Create Maven project to check code quality
Install sonar scanner-->
https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/
set the path-->Example
C:\Users\Mathurangini\Downloads\sonar-scanner-cli-4.0.0.1744-windows\sonar-scanner-4.0.0.1744-windows\bin
Install SonarQube-->Community edition
https://www.sonarqube.org/downloads/
[https://docs.sonarqube.org/latest/setup/get-started-2-minutes/]

# On Windows, execute:
C:\sonarqube\bin\windows-x86-xx\StartSonar.bat

#add sonar-project.properties on project file
it includes-->
sonar.projectKey=sonar-example
sonar.projectName=sonar-example
sonar.projectVersion=1.0
sonar.sources=src
sonar.java.binaries=.

#Start the sonar-scanner.bat file on project file
