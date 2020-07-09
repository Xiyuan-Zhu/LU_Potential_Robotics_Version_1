LU_Potential_Robotics
This README is designed in a way that assumes that the host has installed Docker and has the latest version of f1tenth_gym_ros

1. Git clone the following .py, .launch, and .csv files from https://github.com/Lu-Potential/LU_Potential_Robotics.git 
into the subfolder /src/f1tenth_gym_ros-master/scripts of your catkin workspace.

2. Create a path in the Home folder called "~/rcws/logs/" or path name of your choice 
(This direction was taken from the readme.md file in the particle_filter package)
and copy the .csv file into the 'logs' folder.

3. Start a docker container

4. In a different terminal, catkin_make, source devel/setup.bash, and run:
    $roslaunch f1tenth_gym_ros 'something'.launch
