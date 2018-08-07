# Terminal Command

## Git
### 1)git add .
### 2)git commit -a -m "add .md"
### 3)git clone https://github.com/24k-milk/24k-milk.git

## ROS
### Turtle
roscore[^Master]  
rosrun turtlesim turtlesim_node[^OpenUp Node]  
rosrun turtlesim turtle_teleop_key[^Keyboard Operating]  
[Key Value]:<>(
^[[A up  
^[[B down  
^[[C right  
^[[D left  
)

rostopic list[^Topic List]  
rostopic info /turtle1/cmd_vel[Show Publisher Subscriber and Other Information]  


### Make Workspace and Compile Package
mkdir -p {workspace}[^Create Workspace directory]  
cd {workspace}  
catkin_make  
cartkin_create_pkg {pkgname} rospy {lang}  
cd {workspace/devel/}   
source setup.bash  
mkdir {pkgname}/launch  
touch {topicname}.launch  
gedit .  

#XML



* [name](http://www.baidu.com)
