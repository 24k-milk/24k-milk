# Terminal Command

## Git
### 1)git clone https://github.com/24k-milk/24k-milk.git https://github.com/Bangbiu/ros_note.git
### 2)git add .
### 3)git commit -a -m "add .md"

## ROS
### Turtle
* [Master]  
*roscore*  
* [OpenUp Node]  
rosrun turtlesim turtlesim_node  
* [Keyboard Operating]  
rosrun turtlesim turtle_teleop_key  
>[Key Value]
>[[A up  
>[[B down  
>[[C right  
>[[D left  


* [Topic List]  
rostopic list  
* [Show Publisher Subscriber and Other Information]  
rostopic info /turtle1/cmd_vel  


### Make Workspace and Compile Package
* [Create Workspace directory]  
mkdir -p {workspace}  
cd {workspace}  
catkin_make  
cartkin_create_pkg {pkgname} rospy {lang}  
cd {workspace/devel/}   
source setup.bash  
mkdir {pkgname}/launch  
touch {topicname}.launch  
gedit .  

#XML



* [BAIDU](http://www.baidu.com)
