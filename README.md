# Stereo_Vision
Stereo vision project mainly  consists of 9 steps"
1. Camera calibration and getting calibration files: https://github.com/Mayakshanesht/Kalman-and-bayesian-filters/blob/master/Calibration.ipynb
2. loading images from both the cameras
3. calculating disparity maps using stereo_block matching approach and stereo semi-global block matching approach
4. load calibration parameters again to get the focal length and baseline length between two cameras
5. calculate Depth map
6. do obstacle detection using YOLOv4(tiny model)
7. get obstacle distance by  merging knowledge from depth map and object detection algorithm
https://drive.google.com/file/d/1-6WVLLUcc16KsNu3AwL8zHDGl0MEy16C/view?usp=sharing
8. 3D reconstruction 
9. pseudo-Lidar visualization
