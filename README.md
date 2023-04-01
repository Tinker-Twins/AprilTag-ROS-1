# AprilTag ROS 1
AprilTag Detection and Tracking with ROS 1

## Build:
1. Make a directory `ROS1_WS` to act as your ROS 1 workspace.
    ```bash
    $ mkdir -p ~/ROS1_WS/src/
    ```
2. Clone this repository:
    ```bash
    $ git clone https://github.com/Tinker-Twins/AprilTag-ROS-1.git
    ```
3. Build the packages.
    ```bash
    $ cd ~/ROS1_WS
    $ catkin_make_isolated
    ```
4. Source the `setup.bash` file of your `ROS1_WS`.
    ```bash
    $ echo "source ~/ROS1_WS/devel_isolated/setup.bash" >> ~/.bashrc
    $ source ~/.bashrc
    ```

## Execute:
```bash
$ roslaunch apriltag_ros apriltag_ros.launch.py
```
