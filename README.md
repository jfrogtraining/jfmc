# jfmc

This document is prepared for JFMC Swampup 2016 class.

# JAVA 8 Installation
        Run java –version
        Please make sure that you have JDK 8 update 45 and above.
        If java –version lower than JDK8 then pull Java 8 using java8-installation command based on the environment.
        Click on respected file and install
        Update JAVA_HOME to point to JDK 8 installation
        Verify java –version 
        Verify Java home
        Which java

# Artifactory Installation
        If no local Artifactory installed then go to next step
        Download zip file using artifactory-pull-cmd file
        Unzip the file
        Run bin\artifactory.bat for Windows or bin\artifactory.sh

# JFMC Installation
        If no local Jfrog Mission Control installed then go to next step
        Download ZIP file using jfmc-pull-cmd file
        Unzip the file
        Run bin\mission-control.bat for Windows or bin\mission-control.sh
# Download license file
        Download license file using download-license file commands
# New user creation using REST API
        Please use new-user-creation-cmd file command to run curl command
# New local repository creation
        Please use repo-creation-script
# New local repository creation and replication setup script
        Please use repo-replication-setup-script
            Script CreateLocalRepo - Creates a local repository based on user input
            Script CreateMultiPushReplication - Setup STAR topology replication between master and child local repository
