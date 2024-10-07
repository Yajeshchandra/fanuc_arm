# FANUC Arm Workspace

This repository contains the necessary configurations and scripts to work with the FANUC robotic arm using ROS and MoveIt.

## Setup Instructions

1. **Source the repository:**

    ```bash
    source /home/ub20/test_fanuc_arm_ws/devel/setup.bash
    ```

2. **Launch the MoveIt demo:**

    ```bash
    roslaunch moveit_resources_fanuc_moveit_config demo.launch
    ```

    Note: Fake execution is enabled, which will simulate the robot as if it were in a Gazebo simulation.

3. **Run the test script:**

    ```bash
    rosrun moveit_resources_fanuc_moveit_config test.py
    ```

## Additional Information

For more details, refer to the official MoveIt and ROS documentation.
