# Kumar-Portfolio
Major projects in recent years

# Project 1: ![Computer Vision Solutions for Perception in Small Autonomous Racecar Systems](https://github.com/kumarapurv/Object-Detection-and-Depth-Sensing-for-a-Small-Autonomous-Racecar-System)
- Built the perception stage of a racecar to run on `NVIDIA Jetson TX2` and used `ZED Stereo Camera` for visual input
- Developed in `Python 2` using `Robot Operating System (ROS)`
- Used `YOLO` to extract the detected objects in the racecar’s environment
- Estimated distances of these objects from the camera using stereo camera parameters
- Forwarded the perception data to the master controller of the ROS node (to perform the next steps, i.e., planning and control of the racecar)
- Algorithm is designed to perform high-speed calculations and work in real-time

![Final Output shows objects detected along with their distances (in meters) from the stereo camera](https://github.com/kumarapurv/Object-Detection-and-Depth-Sensing-for-a-Small-Autonomous-Racecar-System/blob/main/demo/output_1.gif)
