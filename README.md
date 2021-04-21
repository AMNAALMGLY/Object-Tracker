# Object-Tracker
we will build a simple object tracker  on all frames of a video and then will link the predictions from one frame to the next using detectron2 mask RCNN FPN.This is project for [AMMI](https://aimsammi.org/) computer vision 2 course taught by [Ross Girshick](https://www.rossgirshick.info/)
![alt text](https://github.com/AMNAALMGLY/Object-Tracker/blob/main/00.jpg?raw=true)
# Video link
https://github.com/gkioxari/aims2020_visualrecognition/releases/download/v1.0/videoclip.zip 

# Part A: Detecting Objects in Frames
Download a small video clip of 41 frames from the link above and Visualize the predictions from a random set of frames

# Part B: Tracking Objects in Pairs of Frames
Implement this pairwise tracker for consecutive pairs of frames in the video clip and visualize the pairs of predictions which were linked based on a linking algorithm(intersection over union and eucledian distance).Visualization of  multiple pairwise tracks for the same two consecutive frames  is done by colorcoding  predicted tracks

# Part C: Tracking Objects in Videos
perform pairwise links for a time horizon of 10 frames. Visualize examples of 10-frame trackes and  colorcode the tracks
- [More discription of the methodolgy and results](https://github.com/AMNAALMGLY/Object-Tracker/blob/main/object%20tracker%20methods%20and%20results.pdf)
- [Run the code yourself!](https://github.com/AMNAALMGLY/Object-Tracker/blob/main/object_tracker.ipynb)
