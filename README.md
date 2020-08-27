# Instructions for simulation

## Running Followerstopper

0. Prerequisite: You must have ROS Melodic installed and a catkin workspace into your system. Read the README of catvehicle repo first to meet the expectations.

1. Follow the instruction on README of https://github.com/jmscslgroup/catvehicle to install ROS, CAT Vehicle testbed by cloning the repo at commit 72e888f5407aa2a52d4cc341a27aa1b8b45d2041
```python
git clone https://github.com/jmscslgroup/catvehicle
cd catvehicle
git checkout 72e888f5407aa2a52d4cc341a27aa1b8b45d2041
```
Then followe the instruction in README of catvehicle repo to make sure that all packages and drivers are installed. If encounter any issue, contact/send message for resolution

2. Open the `fs.slx` file  `kf.slx` provided in this repo in MATLAB and generate standalone ROS node into your catkin workspace.

3. Running the followerstopper

Terminal 1:
-------------

```
roslaunch catvehicle fs-test1.launch
```

Terminal 2:
-------------

Capture bagfile:


```
rosbag record -a -o fs-test1
```

4. For analyzing bafile, look at the notebook in `bagfiles/fs-test1.ipynb` of this repo.



# Author
Rahul Bhadani

Copyright (c) Rahul Bhadani; Jonathan Sprinkle; The University of Arizona
All rights reserved
