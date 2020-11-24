# j2n6s200_moveit_config
kinova jaco2 6-dof 2f-gripper moveit config 

# start
## for fake control
```bash
roslaunch j2n6s200_moveit_config demo.launch
```

## for real control
```bash
#launch kinova driver
roslaunch kinova_bringup kinova_robot.launch kinova_robotType:=j2n6s200
#launch moveit config
roslaunch j2n6s200_moveit_config j2n6s200_execute.launch
```
