# Terminal

# Git
git add .
git commit -a -m "add .md"
git clone https://github.com/24k-milk/24k-milk.git
# ROS

roscore

## rosrun turtlesim turtlesim_node 
## rosrun turtlesim turtle_teleop_key 

^[[A up
^[[B down
^[[C right
^[[D left



rostopic list
rostopic info /turtle1/cmd_vel

#XML

mkdir -p {workspace}
cd {workspace}
catkin_make
cartkin_create_pkg {pkgname} rospy {lang}
cd {workspace/devel/} 
source setup.bash
mkdir {pkgname}/launch
touch {topicname}.launch
gedit .




*[name](http://www.baidu.com)
