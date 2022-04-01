# motive_sandbox
Experimental repository for using motive and vrpn_ros_client

# Usage
1. Set a rigid body on the motive with the name `test`
2. Set the ip address of the windows pc where motive works to `192.168.0.10`
3. Properly connect between Ubuntu and windows pc according to the ip address 
4. `roslaunch motive_sandbox motive_vrpn_test.launch`

If you use a different name or ip address, please modify launch, config etc.

# Dependencies
Refer to package.xml to install the required dependent packages.
```sh
cd ~/catkin_ws
rosdep install -i --from-paths src
```