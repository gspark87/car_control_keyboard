# car_control_keyboard

This package is for RC car keyboard control.  
The control code for the target RC car is [here][control_code].

[control_code]: https://github.com/gspark87/car_control

- ROS2 Galactic

## Build

    colcon build --package-select car_control_keyboard
    source install/setup.bash

## Run

    ros2 run keyboard_control keyboard_control

## Reference
https://github.com/ros2/teleop_twist_keyboard
