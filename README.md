# Welcome to Kumar's Portfolio

Here's a sneak peek into some of my works

## Project 1: [Perception for a Small Autonomous Racecar Systems](https://github.com/kumarapurv/Object-Detection-and-Depth-Sensing-for-a-Small-Autonomous-Racecar-System)
- Built the Racecar's platform using `Nvidia Jetson TX2` as the processing unit and `ZED Stereo Camera` as visual input
- Developed perception algorithm in `Python 2` using `Robot Operating System (ROS)`
- Object detection in racecar's environment using `YOLO v3`
- Distance estimation of these objects using stereo camera parameters
- Forwarded the perception data to the master controller of the ROS node (to perform the next steps, i.e., planning and control of the racecar)
- The algorithm was designed to perform high-speed calculations and work in real-time

![](/images/output_1.gif)

_Fig: Output shows bounding box around detected objects, with class labels and their estimated distance (in meters) on top_

## Project 2: [Sentiment Analysis on Twitter Data](https://github.com/kumarapurv/Sentiment-Analysis-on-Twitter-Dataset-using-Machine-Learning-)
- Determined the emotional coloring of twits (a positive or negative sentiment) using various Machine Learning models
- Performances of several ML models mentioned below were compared
  1. Support Vector Machines
  2. Multinomial Naive Bayes
  3. Bernoulli Naive Bayes
  4. Decision Trees
  5. Logistic Regression
- The best performing model was picked to perform further analysis
- Achieved an accuracy of 76.5% and an F1-score of 0.8

![](/images/rocauc_comparison.png)

_Fig: ROC - AUC of all Machine Learning Models used_
