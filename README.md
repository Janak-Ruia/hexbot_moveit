# hexbot_moveit
This repo includes the configuration files for the moveit package. For running the simulation in rviz, type :
roslaunch hexbot_moveit_config demo.launch

After the robot planner has loaded, run :
rosrun hexbot_moveit_config x.py

Now, just follow the terminal prompts, and enter the desired pose names to plan them:
straight_ahead 
place_on_bot_1
place_on_bot_2
place_on_bot_3
gripper_closed
gripper_open
attach_box
detach_box
go_down - this will initiate a sequence of moves to place the torus into the gripper
