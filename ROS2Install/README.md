## Install ROS 2 on Ubuntu
The below script installs compatible ROS 2 version after checking the Ubuntu Version

## Install Script
### Install script for installing ROS 2 on Ubuntu
### To install do the following from your command prompt: 

```
sudo apt-get update
sudo apt-get upgrade
wget https://raw.githubusercontent.com/VEEROBOT/ros-scripts/main/ROS2Install/install_ros2.sh
chmod 755 ./install_ros2.sh
sudo bash ./install_ros2.sh
```
### The script will take upto 15 minutes to install. 


```
sudo apt-get update
sudo apt-get upgrade
wget https://raw.githubusercontent.com/VEEROBOT/ros-scripts/main/ROS2Install/install_ros2_v2.sh
chmod +x install_ros2_v2.sh
./install_ros2_v2.sh
```

### Errors
If for some reason, wget is not able to connect, add raw.githubusercontent.com ip to hosts file

```
sudo nano /etc/hosts
185.199.108.133 raw.githubusercontent.com
```
Save, Close and Try again. In some cases, you may have to restart the system. You can also set DNS 8.8.8.8 on your network to resolve this

