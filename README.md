# SLAM-based-Navigation-Stack

SLAM based Navigation Stack implementation using AMCL Localisation 

Follow this steps to run this package in your systems: 

Step 1: Change your directory to catkin_ws/src/

```python
cd ~/catkin_ws/src
```

Step 2: Paste this command in terminal to clone the repository pkg in your workspace. 

```python
git clone https://github.com/ROBODITYA/SLAM-based-Navigation-Stack.git
```

Step 3: Now build your catkin_ws and execute bellow command in separate terminals.

```python
roslaunch rmp_bot_description gazebo.launch
```

open another terminal and paste bellow command.

```python
roslaunch rmp_bot_description navigation.launch
```

Step4: Now in Rviz give the 2D nav goal to move your bot on specific location.

