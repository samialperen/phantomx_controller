# phantomx_controller


## How to Start

```
roslaunch pxpincher_launch pxp.launch 
```


```
roslaunch phantomx_pincher_robot_arm_edited_moveit_config arm.launch 
```

```
roslaunch openni2_tracker tracker.launch 
```

```
rosrun openni2_tracker_listener skeleton_tf_listener 
```

```
rosrun openni2_tracker_listener feature_extraction.py
```

```
rosrun phantomx_controller phantomx_controller_node.py
```

## Dependencies

* https://github.com/rst-tu-dortmund/phantomx_rst #For kinetic, add "add_compile_options(-std=c++11)" to the cmakelists of the every package in the phantomx_rst metapackage.
* https://github.com/samialperen/openni2_tracker
* https://github.com/samialperen/openni2_tracker_listener
* OpenNI2
* NITE2






