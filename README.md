# NTU_RobotSim_Nav2
NTU Robot Simulation for Nav2 using ROS 2 Humble and Gazebo Fortress

## Building the Project

from your workspace folder
```bash
colcon build --symlink-install
```

## Launching Simulations

### Launch Maze Simulation
```bash
source install/setup.bash
ros2 launch ntu_robotsim maze.launch.py
```

### Then in a Different Terminal, Launch Single Robot Simulation
```bash
source install/setup.bash
ros2 launch ntu_robotsim single_robot_sim.launch.py
```
