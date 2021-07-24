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
Jenkins pipeline syntax used for defining JenkinsFile on your .mdfile on Github. <br/>Source(git) ----Build/package --Deploy.

**Pipeline**

It is a user-defined framework that includes all the processes like create, check, deploy, etc. In a Jenkinsfile, it’s a list of all the levels. All of the stages and steps within this block are described. This is the fundamental block to the syntax of a declarative pipeline.

**Agent Any**

Where to execute
An agent is described as a directive that can run multiple builds using just one Jenkins instance. This feature helps spread the workload to various agents and execute multiple projects within Jenkins’s single instance. It instructs Jenkins to assign the builds to an executor.

A single agent may be defined for a whole Jenkins pipeline, or different agents may be assigned to execute each stage within a pipeline. Some of the most commonly used Agent parameters are:

Any
Runs the stage pipeline on any available agent.

**Stages**

This section includes all of the work that needs to be completed. The work is defined in the form of stages. Within this Directive, there may be more than one level. Each stage executes a particular task.

**Steps**

Within a stage block, the pipeline can be described as a series of steps. Such steps are performed in sequence for the execution of a level. Within a Steps guideline, there must be at least one step.
script that executes a command on the Jenkins server



