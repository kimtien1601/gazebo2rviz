# gazebo2rviz
Automatically import all entities simulated in ROS-enabled Gazebo or described in a set of SDF files into rviz through the TF  and Marker plugin. Furthermore add objects from a SDF as MoveIt collision objects.

## Requirements
- ROS Noetic
- pysdf: `git clone git@github.com:andreasBihlmaier/pysdf.git`

## Running
- Load `test.sdf` file to rviz:
  `roslaunch gazebo2rviz test_sdf2rviz.launch`