# fetch_train

how to make fetch train packages   
catkin_create_pkg fetch_train std_msgs geometry_msgs trajectory_msgs rospy roscpp openai_ros message_generation  


virtual environmet setting   
. ~/path/to/venv/bin/activate  

pip install mpi4py  
pip install theconstruct_msgs   
git clone https://bitbucket.org/theconstructcore/theconstruct_msgs.git  

virtual environmet run trian.py   

. ~/path/to/venv/bin/activate  
roscore  
python ~/catkin_ws/src/fetch_train/scripts/train.py  

///////////////need test//////////////////////////////////////  

roslaunch fetch_moveit_config fetch_planning_execution.launch  
roslaunch tetch_moveit_config fetch_planning_execution.launch  
rosrun fetch_train execute_trajectories.py  

//////////////etc /////////////////////////////////////////////  
https://rds.theconstructsim.com/tc_projects/use_project_share_link/f2883cee-5fd8-41d6-bd5f-09b33862860b  
https://github.com/fetchrobotics/fetch_gazebo.git  
https://bitbucket.org/theconstructcore/fetch_tc/src/r0-kinetic/  
