# Introduction
This is the official repo for IITISOC by 
- Mohit Naval - [GitHub](https://github.com/Mohit-Naval) [LinkedIn](https://www.linkedin.com/in/mohit-naval-39a64b234?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
- Bhavy Ranka - [GitHub]() [LinkedIn](https://www.linkedin.com/in/bhavy-ranka-100770321) 
- Abhinav Jain - [GitHub]() [LinkedIn](https://www.linkedin.com/in/abhinav-jain-852534313/)                                                                                                                                                                                               

We are working on Swarm implementation using Gazebo,SLAM Toolbox
## Resources
For our PS we are reffering to 
- [GitHub Repo](https://github.com/YePeOn7/ros2_omni_robot_sim.git)
- [Humble Documentation](https://docs.ros.org/en/humble/index.html)
- [Gazebo Documentation](https://gazebosim.org/docs/fortress/getstarted/)


## Getting Started

### Prerequisites
- Install ROS2 Humble
- Install Gazebo for humble (Gazebo Fortress)
- Install Slamtoolbox for humble
```bash
sudo apt install ros-humble-slam-toolbox
```

### Let's get going
1. Clone the HUMBLE branch of [repo](https://github.com/YePeOn7/ros2_omni_robot_sim.git) in ros2_ws by-
```bash
git clone -b humble https://github.com/YePeOn7/ros2_omni_robot_sim.git
```
2. Follow along the steps mentioned in the Repo.


## Some helpful commands
- Command to check branch version you cloned
```bash
git status
git branch
```


## Troubleshooting some common errors
### Xacro
If you encounter a error stating, No such file or directory as 'xacro'. Then use the following command
```bash
sudo apt update
sudo apt install ros-humble-xacro
```

### ROS Gazebo Bridge not found
Error:
```bash
PackageNotFoundError: package 'ros_gz_bridge' not found
```
Soluiton:
```bash
sudo apt update
sudo apt install ros-humble-ros-gz-bridge
```
