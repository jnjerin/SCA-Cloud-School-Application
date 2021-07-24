# SCA-Cloud-School-Application
This is a project that's part of my SCA Cloud School application.

Task:<br/>
Create an AWS EC2 instance and install Jenkins<br/>
Create a repository on github and integrate it to Jenkins<br/>
Set up a build job on Jenkins


**JENKINS ACCESS:**<br/>
http://18.217.73.24:8080/<br/>
username: njeri<br/>
password: njerij

Jenkins Build Syntax


**Pipeline**

It's the fundamental block to the syntax of a declarative pipeline.
In a Jenkinsfile, it’s a list of all the levels. All of the stages and steps within this block are described. 

**Agent Any**

Where to execute
An agent is described as a directive that can run multiple builds using just one Jenkins instance. It instructs Jenkins to assign the builds to an executor.

A single agent may be defined for a whole Jenkins pipeline, or different agents may be assigned to execute each stage within a pipeline.
          **Any**
            Runs the stage pipeline on any available agent.


**Stages**

This section includes all of the work that needs to be completed. Each stage executes a particular task.
The stages on my syntax are:
Build
Test 
Deploy


**Steps**

Within a stage block, the pipeline can be described as a series of steps. Such steps are performed in sequence for the execution of a level.
The script in a step executes a command on the Jenkins server
On my syntax
echo "echo 'Building the application...'   This command will display the message 'Building the application'



