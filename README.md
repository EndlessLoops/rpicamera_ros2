Install:

$ sudo apt install ros-foxy-image-tools ros-foxy-usb-cam ros-foxy-compressed-image-transport
$ cd ~/ros2_ws/src
$ git clone https://github.com/EndlessLoops/rpicamera_ros2.git
$ colcon build --packages-select rpicamera_ros2

Usage:


$ ros2 launch rpicamera_ros2 rpicamera.launch.py
$ ros2 run rqt_image_view rqt_image_view 

