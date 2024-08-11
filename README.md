# SOAR-EDR-Project


## Objective

The goal of this project was to create my own detection and response tools and to create playbooks for automation. As a plus I got to familiarize myself with some EDR/SOAR tools like LimaCharlie and Tines. 

### Skills Learned



## Part 1
For the first part of this project, I created a playbook workflow and branstormed about what actions I wanted it to take. I drew out the workflow with these key points in mind: A computer gets infected, LimaCharlie sends that detection/Alert over to Tines. Tines then generats a message and sends that message containing some useful info about the detection. Tines sends the message to slack or to an email. Tines also prompts the user if they want to take an action. If the user wants to take an action, then LimaCharlie quarantines the infected computer. If the user wishes to not take an action, then no action from LimaCharlie is required but they will be a message to please investigate. You can see a visual representation of this workflow below: 

## Ref 1: Visual Representation of Playbook
