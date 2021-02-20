# Welcome to Kumar's Portfolio

Here's a sneak peek into some of my works

## Project 1: [Computer Vision Solutions for Perception in Small Autonomous Racecar Systems](https://github.com/kumarapurv/Object-Detection-and-Depth-Sensing-for-a-Small-Autonomous-Racecar-System)
- Built the Racecar's platform using `Nvidia Jetson TX2` as the processing unit and `ZED Stereo Camera` as visual input
- Developed perception algorithm in `Python 2` using `Robot Operating System (ROS)`
- Object detection in racecar's environment using `YOLO v3`
- Distance estimation of these objects using stereo camera parameters
- Forwarded the perception data to the master controller of the ROS node (to perform the next steps, i.e., planning and control of the racecar)
- The algorithm was designed to perform high-speed calculations and work in real-time

![Output shows bounding box around detected objects, with class labels and their estimated distance (in meters) on top](https://github.com/kumarapurv/Object-Detection-and-Depth-Sensing-for-a-Small-Autonomous-Racecar-System/blob/main/demo/output_1.gif)
