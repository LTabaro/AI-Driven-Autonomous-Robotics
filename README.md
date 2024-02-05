# AI-Driven Autonomous Robotics: Human Tracking and Reactive Behaviour Analysis using AI and Sensing Technologies


### Aims
This project aims to design and implement a program in Python to control mobile robots which will guide a robot on how to effectively manoeuvre its way through an environment while tracking an instance of a human or multiple humans using the pre-trained [ssd_mobilenet_v2_coco](https://docs.openvino.ai/2021.4/omz_models_model_ssd_mobilenet_v2_coco.html) for object detection.
. Additionally, the project seeks to implement several robot reactive behaviours and high level behaviours.

### Main tasks:

* Part A: Reactive behaviours -- demonstrate the following four Braitenberg behaviours:  Aggression, Fear, Love as Curiousity.   

* Part B: Following behaviour -- the robot follows a person whilst maintaining a safe distance. The robot should avoid collisions with the object's in the environment and the person it's tracking. In the event where there is more than one human visible to the robot, it is capable of detecting all humans visible in the frame but will only track and follow the movements of the human which is closest to the camera by calculating the distance of all visible humans and prioritising that which is closest.     


### Objectives:
* Design and implement a program in Python which controls the movements of a robot.
* The robot to adhere to the four Braitenberg behaviours. 
* The robot to detect a human using the pretrained model. 
* The robot to track and follow a human’s movements whilst maintaining a safe distance. 
* The robot to avoid collisions with humans and other obstacles.  
* The robot to track and follow only one human at an instance.

**Further Information:**   

This project will use mobile robots built with the latest AI and sensing technology. The robots have a latest Realsense camera from Intel, a Nano board from Nvidia to support image processing and deep learning etc, proximity sensors, IMU, motors and driving circuits.  
