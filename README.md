# 6DOF-Tool_PLC-HMI

# Purpose of this Repository
This repsoitory is not a complete project, and does not contain all the files needed to run such a project on a PLC. 

The purpose of this repository is to showcase some of the work I have completed for programming PLCs using Structured Text. 

All the files in this repo I either created, colaporated on, or edited. 

Within the POUs directory there is a "Top_LeveL_Control.TcPOU" file that functions as the "main" program file. 

# The Project
The project contained two robotic tools: one 6DOF positioning tool and one 9-camera array monitoring tool. 
The Positioning Tool featured 3 ball-screw jacks configured in a circular pattern sepatated by 120 degrees. These jacks were responsible for translation along the z-axis as well as rotation about the x and y axes. Three additional servos controlled x translation, y translation, and z rotation. 

The system featured a Touchscreen Human Machine Interface (HMI). The touchscreen consited of multiple screens for user authentication, alarm & warning monitoring, sensor information, and motion control calibration and settings. Axis motion control was completed using momentary toggle switches. 

The rest of the HMI consisted of a 6 monitor array for monitoring the video signal from the cammera array. 
