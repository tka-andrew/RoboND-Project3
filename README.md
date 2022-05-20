# Udacity Nanodegree - Robotics Software Engineer - Project3

This is my project submission for Project3: Where I Am of [Udacity Nanodegree - Robotics Software Engineer](https://www.udacity.com/course/robotics-software-engineer--nd209?irclickid=U9u1PgV1xxyIROOV3m3wlTMuUkD0yqTMORvH3A0&irgwc=1&utm_source=affiliate&utm_medium=&aff=2298976&utm_term=&utm_campaign=__&utm_content=&adid=786224).

## Usage
1. Git clone this workspace
2. `cd` into this workspace and build:
    ```
    mkdir build
    catkin_make
    ```
3. Source the workspace:
    ```
    source devel/setup.bash
    ```
4. Launch the simulation world and amcl nodes
    ```
    roslaunch my_robot world.launch
    roslaunch my_robot amcl.launch
    ```
5. Rosrun the teleop
    ```
    rosrun teleop_twist_keyboard teleop_twist_keyboard.py
    ```