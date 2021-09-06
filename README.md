# RBT32021_AV_Webots_Driverless_Simulation_Competition

## Background

## Webots Controller and World Files
You will be given a 4 wheel Adept Pioneer 3-AT Vehicle. This model includes support for 4 motors and 16 sonar sensors(8 forward facing, 8 rear facing). In out world files, we've added the following sensors:

* Lidar
* Camera
* Inertial Unit Sensors

You will also be given 2 world files each containing a track. Each track consists of cones, where the yellow cones denote the outside of the track and the blue cones denote the inside of the track. 

* NMP_Simple.wbt
* NMP.wbt

## Task
In teams of 3, program the Adept Pioneer 3-AT to autonomously navigate itself around the track for at least one full lap. You can use any of the supported languages to write the robot controller. You may use any combination of sensors to accomplish this. You can also use computer vision and/or machine learning methods in your implementation. Please ensure that your code is readable e.g. add comments. 

Once functional, your goal is to implement one of the following extensions. These extensions can either be integrated into the main assignment or separate from the main assignment. 
* Increased Speed: Program the robot to navigate around the track as fast as possible. 
* SLAM: Generating a map of the track. You can use manual navigation to navigate track in this stage, Hint: This requires use of the Lidar and position sensors 
* Path planning: Given the map, implement a path planning algorithm to optimise lap time. 
* Object Recognition:  Recognise objects in the robot’s paths. There are many ways you can do this. You can use a camera, Lidar, e.t.c. Webots has a recognition node that can be attached to the camera device that will allow you to implement this! 
* Colour Detection: Use the camera to detect different colours of objects on the path of the track. There are many ways to do this! You can use openCV
* And any other extensions you would like to implement!

## Resources

Webots Tutorials:

Webots Documentation:


## How to use the Manual Controller

## Submission