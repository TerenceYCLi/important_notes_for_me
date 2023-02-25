# important_notes_for_me

# Gazebo tutorial link
1. for launch file : https://classic.gazebosim.org/tutorials?tut=ros_roslaunch
2. build world file: https://classic.gazebosim.org/tutorials?cat=build_world

# OpenCV 
1. camera model 
https://docs.opencv.org/2.4/modules/calib3d/doc/camera_calibration_and_3d_reconstruction.html
2. Pythoncode
https://medium.com/analytics-vidhya/the-ultimate-handbook-for-opencv-pillow-72b7eff77cd7#:~:text=Note%3A%20OpenCV%20images%20are%20in,format%20from%20one%20to%20another.

# conda and Ros will crash
1. conda config --set auto_activate_base false to disable the conda env
2. conda config --set auto_activate_base true to enable the conda env


# Problem to solve for LiDaR NeRF
1. the model after training need so many time to render, can not use in realtime rendering sence.


# trick to train depth nerf
1. first need to scale the depth map to the same size as rgb.
2. for polycam ns-process-data polycam --use-depth --data ./poly.zip --output-dir ./ready_for_use_depth
3. ns-train depth-nerfacto --data ./
4. transform.json has the depth image path under the img_path

# Python path usage
1. from pathlib import Path
a = Path("iamhere")
b = a / "haha"
print(b) # b = "iamhere/haha"

# for segmentation image
1. example of segment a lung
https://github.com/lukepolson/youtube_channel/blob/main/Python%20Tutorial%20Series/image_processing1.ipynb

