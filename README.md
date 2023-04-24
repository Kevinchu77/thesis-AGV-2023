# thesis-AGV-2023

echo $GAZEBO_MODEL_PATH 
#thay doi model

catkin_make: build code sau khi clone

#sau khi khoi dong lai
source devel/setup.zsh: chon n model su dung
roslaunch: launch program--- tab tab

#sua world bat den

#chay teleop
osrosrun teleop_twist_keyboard teleop_twist_keyboard.py

#luu map
rosrun map_server map_saver -f mymap

#up map da luu truoc
Note: phai vao folder chuwa map truoc khi dung
rosrun map_server map_server map_warehouse_1.yaml


/cmd vel: toc do linear & regular
rostopic list: show topic
rostopic echo /_topic_ : show messages to topic
#tf_frame
rosrun rqt_tf_tree rqt_tf_tree

#transform frame to frame
check frame in rqt_tree
then check the transform in cmd with this code
rosrun tf tf_echo odom carcaca

#doi ten carcaca
voo source code
doi thanh base_link
chir chon file mem
#topic scan / transform base_link to laser check
#install package
sudo apt install ros-noetic-_____

#Tu dong do map
cac buoc co ban
sau do export robot trung turtlebot3
export TURTLEBOT3_MODEL=waffle_pi

#robot moi
roslaunch turtlebot3_gazebo robot_turtle.launch

