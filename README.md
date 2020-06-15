# Tools-For-ROS
10 THINGS TO DO BEFORE STARTING WITH ROS | Setting Up Ubuntu with Useful Tools for ROS Installation

### Updating & Upgrading Ubuntu
```
sudo apt-get update && sudo apt-get upgrade
```

### Solving Time Issue After Dual Boot
```
timedatectl set-local-rtc 1 --adjust-system-clock
```

### Install Terminator
```
sudo add-apt-repository ppa:gnome-terminator
```
```
sudo apt-get install terminator
```

### Install Sublime Text
```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```
```
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```
```
sudo apt-get update
```
```
sudo apt-get install sublime-text
```
```
subl
```

### Important Linux Packages
```
sudo apt-get install libavcodec-dev libsdl1.2-dev xsltproc libbullet-dev libsdl1.2-dev libgoogle-glog-dev protobuf-compiler python-wstool
```

### Install Gazebo
If you are using Ubuntu 16.04, download Gazebo 7
```
sudo apt-get install gazebo7 libgazebo7-*
```
Or else if you are using Ubuntu 18.04, download Gazebo 9
```
sudo apt-get install gazebo9 libgazebo9-*
```

### Install Arduino IDE
Open up a terminal in arduino folder and then type this command
```
sudo ./install.sh
```

### Install GIT
```
sudo apt-get install git
```
