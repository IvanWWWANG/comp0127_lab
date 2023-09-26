# comp0127_lab
Collection of packages for lab sessions in COMP0127 Robotic Systems Engineering.

## Installation Instructions:
https://liveuclac-my.sharepoint.com/:b:/g/personal/ucabkdo_ucl_ac_uk/EWt6vYuADftImZkMphNJnL8BxgSDYuhTeKM6BsSFMaJZPA?e=rz367f


## Ubuntu 20.04 and ROS 1 Noetic Setup

Note:
This course is designed using **ROS 1 noetic** (a.k.a. ROS noetic) in a **Ubuntu 20.04** environment.
Newer releases of Ubuntu (e.g. Ubuntu 22.04 or Ubuntu 23.04) are **NOT** compatible with ROS 1.
Attempting coursework using ROS 2 distributions will result in compatability issues.

Ubuntu 20.04 releases available for download at:
https://releases.ubuntu.com/focal/

If you do not have Ubuntu 20.04 as your default OS, it is recommended that you set up Ubuntu 20.04 in a virtual environment. Instructions for setting up Ubuntu 20.04 are available on moodle.

In a Ubuntu 20.04 environment, install ROS noetic by following the installation instructions available at:
http://wiki.ros.org/noetic/Installation/Ubuntu


## com0127_lab Dependencies

Once ROS noetic is installed, run the following code in a Ubuntu command terminal:
```
sudo apt install ros-noetic-controller-manager ros-noetic-joint-state-controller ros-noetic-effort-controllers ros-noetic-gazebo-ros-control ros-noetic-joint-trajectory-controller ros-noetic-velocity-controllers ros-noetic-ros-controllers ros-noetic-ros-control
```

References:
- youbot_description: 'https://github.com/youbot'
- manipulator_h_description: 'https://github.com/ROBOTIS-GIT/ROBOTIS-MANIPULATOR-H'
- open_manipulator_description: 'https://github.com/ROBOTIS-GIT/open_manipulator'

