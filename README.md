# jetbot_ros_melodic

* dusty-nv 
* https://github.com/dusty-nv/jetbot_ros

jetbot_ros 는 이미 ros2 로 많이 넘어갔고 따로 branch를 건드리고 또 내부에 cmd_vel controller 가 없기에 빠르게 테스트용으로 ros1 melodic, jetbot_ros package를 만든다.


`roscore`, `sourcing` 이 되어있다는 전제하에..

```bash
#Terminal #1
rosrun jetbot_ros_melodic jetbot_motors.py
```

```bash
#Terminal #2
rosrun teleop_twist_keyboard teleop_twist_keyboard.py

#sudo apt-get install ros-noetic-teleop-twist-keyboard
```

