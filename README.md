# MD-S00-AGGREGATE-PROJECT

MD-MICROSERVICES-APPLICATION: 
     PARENT-PROJECT-AND-BLANKET-REPOSITORY

This repo is meant to serve as a Central "project-wide hub" for the various microservices contained within the "M&D Web-App" domain.
While its main function is the facilitation of an atomic (...ish) Backup & Restore process on a semi-regular basis (I call it a 'snapshot machine,') it also serves quite a few other secondary purposes. For example, it will serve as:

a tool for checking the breadth of the Production environment (determining which of the services have already been rolled out, and which of them are still in the 'initial development' phase) at any given time (at least until all services have been deployed.)
a hub / base point for various automation pipelines (for CI/CD, Testing, etc.) using Github Workflows.
a tool to help me see, at a glance, which services are ready for beta launch.
    
To this end, Only Services that have passed target tests and been approved as 'ready-to-launch' will go here. 

### VERSIONING:

A seperate fork will be created for each Version of the M&D Build, starting with V 0.0.1.   Each fork will be archived with only those services which were included in that version of the application.


