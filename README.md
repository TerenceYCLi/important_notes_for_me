# important_notes_for_me

# Gazebo tutorial link
1. for launch file : https://classic.gazebosim.org/tutorials?tut=ros_roslaunch
2. build world file: https://classic.gazebosim.org/tutorials?cat=build_world

# OpenCV camera model 
https://docs.opencv.org/2.4/modules/calib3d/doc/camera_calibration_and_3d_reconstruction.html


# conda and Ros will crash
1. conda config --set auto_activate_base false to disable the conda env
2. conda config --set auto_activate_base true to enable the conda env


# Problem to solve for LiDaR NeRF
1. the model after training need so many time to render, can not use in realtime rendering sence.


# trick to train depth nerf
1. first need to scale the depth map to the same size as rgb.

# Python path usage
1. from pathlib import Path
a = Path("iamhere")
b = a / "haha"
print(b) # b = "iamhere/haha"

# for segmentation image
https://github.com/lukepolson/youtube_channel/blob/main/Python%20Tutorial%20Series/image_processing1.ipynb
