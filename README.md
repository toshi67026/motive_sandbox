# motive_sandbox
Experimental repository for using motive and vrpn_ros_client

# usage
1. Set a rigid body on the motive with the name `test`
2. Set the IP address of the windows pc where motive works to 192.168.0.10
3. Properly connect between Ubuntu and windows pc according to the IP address 
4. `roslaunch motive_sandbox motive_vrpn_test.launch`

# dependencies
- ros-noetic environment
- ros-noetic-vrpn-client-ros