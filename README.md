# ROS2_Assignment2

## How to run
### 1. Spawn Obstacle(turtle1)
```python
ros2 run turtlesim turtlesim_node
```

### 2. Spawn Robot(turtle2)
```python
ros2 service call /spawn turtlesim/srv/Spawn "{x: 1, y: 1, theta: 0, name: 'turtle2'}"
```

### 3. Receiving turtle2's present location
```python
ros2 topic echo /turtle2/pose
```

### 4.
