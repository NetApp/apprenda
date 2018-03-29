# ACP extension for DB cloning with NetApp SnapCenter

## Introduction
This automated solution simplifies the process of generating multiple copies of databases on-demand for pre-production purposes. The cloning of a pristine database for Dev/Test is instrumented
automatically at the application deployment time, using native ONTAP features like snapshots and FlexClones via REST API.

At the compute layer, the integrated solution relies on Apprenda deployment policy engine and the abstraction model that frees the developers from the need to know intricacies of database cloning and reduces the need in meetings. 
Apprenda policy engine allows the operators to securely segment the platform based on various needs, SDLC environments being one of them. 
The established policies determine where applications instances are deployed and what databases they are connecting to. 
The databases similar to the applications themselves are segmented based on the deployment policies ensuring secure separation of pre-production and production environments. ​
 Multiple servers can be setup to host cloned databases, in which case Apprenda will be controlling the placement of clones based on the CPU and memory utilization.​


 ### Installation
 Detailed documentation for ACP extension for DB cloning with NetApp SnapCenter can be found on [Read the Docs](http://dbdevtestplugin-docs.readthedocs.io/). 
