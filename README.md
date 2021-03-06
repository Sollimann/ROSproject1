# Project in EE4308 - Advances in Intelligent Systems and Robotics - NUS 2018 #
--------------------------
Turtlebot simulation in Gazebo. The aim of this project is to navigate the turtlebot autonomousely from position (x,y) = (0,0) to (x,y) = (4,4) in a 9m x 9m map with a random arrangement of walls. The project is part of the assessment in the course EE4308 - Advances in Intelligens Systems and Robotics at the National University of Singapore (NUS) during the spring semester of 2018. 


## Requrements ##
--------------------------
Robot Operating System (ROS) Kinetic distribution installed. 


## About the code ## 
-------------------------


## How to run the code ## 
-------------------------
1. Enter your source folder inside your catkin workspace:
	```bash
	$ cd catkin_ws/src
	```

2. Clone the repository: 
	```bash
	$ git clone https://github.com/Sollimann/prj-grp-01
	```

3. Inside your catkin workspace, run:
	```bash
	$catkin_ws catkin_make
	```

4. Run project\_init.sh or project\_init\_world_2.sh to lauch either world 1 or 2:
	```bash
	$ chmod +x project_init.sh
	$ ./project_init.sh
	```
or

	```bash
	$ chmod +x project_init_world_2.sh
	$ ./project_init_world_2.sh
	```

This will launch the turtlebot world. It may take several minuites to load, so be patient! 

5. Launch the launch file navigate\_to\_goal.launch to make the turtlebot navigate towards the target position:

	```bash
	$ roslaunch prj-grp-01 navigate_to_goal.launch 
	```

