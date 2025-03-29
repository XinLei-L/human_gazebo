# human_gazebo

## Source

```shell
https://github.com/TempleRAIL/pedsim_ros_with_gazebo.git
```

> - There is a usage method inside
> - The walking movements of characters need to be improved

## File description

**robot_pedestrians_gazebo.launch**

​	This is a Gazebo runtime file with turtlebot and pedestrians

```shell
roslaunch pedsim_simulator robot_pedestrians_gazebo.launch
```



**airport_activities.launch**

​	This is an rviz running file with a pedestrian model. By modifying `airport_activities.xml`, the number of pedestrians in it can be adjusted. The corresponding parameter is n.

```shell
roslaunch pedsim_simulator airport_activities.launch
```

