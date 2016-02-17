# ROS
pkill -f /opt/ros

pkill -f /"path to your workspace"

to build a single package on the worksapce

catkin_make --pkg package_name


source command to the end of your ~/.bashrc file so that
new terminals will automatically pick up your catkin packages. 

echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc
