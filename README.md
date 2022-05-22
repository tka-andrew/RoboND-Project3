# Udacity Nanodegree - Robotics Software Engineer - Project3

This is my project submission for Project3: Where I Am of [Udacity Nanodegree - Robotics Software Engineer](https://www.udacity.com/course/robotics-software-engineer--nd209?irclickid=U9u1PgV1xxyIROOV3m3wlTMuUkD0yqTMORvH3A0&irgwc=1&utm_source=affiliate&utm_medium=&aff=2298976&utm_term=&utm_campaign=__&utm_content=&adid=786224).

## Usage
1. Git clone this workspace
2. `cd` into this workspace and build:
    ```
    mkdir build
    catkin_make
    ```
3. Source the workspace and roslaunch the world.launch:
    ```
    source devel/setup.bash
    roslaunch my_robot world.launch
    ```
4. Open another terminal and roslaunch the amcl.launc (remember to source the workspace again)
    ```
    roslaunch my_robot amcl.launch
    ```
5. Open a new terminal and rosrun the teleop (remember to source the workspace again)
    ```
    rosrun teleop_twist_keyboard teleop_twist_keyboard.py
    ```
6. Navigate the robot around and observe the arrows.

## Screenshots
![Screenshot01](https://github.com/tka-andrew/RoboND-Project3/blob/master/Screenshots/screenshot01.png?raw=true)

![Screenshot02](https://github.com/tka-andrew/RoboND-Project3/blob/master/Screenshots/screenshot02.png?raw=true)
