# Terminal Command

## Git
### 1)git clone https://github.com/24k-milk/24k-milk.git https://github.com/Bangbiu/ros_note.git
### 2)git add .
### 3)git commit -a -m "add .md"

## ROS
### Turtle
* [Master]  
<font color=red>*roscore*</font>  
* [Open Up Node]  
*rosrun turtlesim turtlesim_node*  
* [Keyboard Operating]  
*rosrun turtlesim turtle_teleop_key*  
>[Key Value]  
>[[A up  
>[[B down  
>[[C right  
>[[D left  

###ROS List
* [Topic List]  
*rostopic list*  
* [Show Publisher Subscriber and Other Information]  
*rostopic info {topicname}*  
* [Listen Events]  
*rostopic echo {topicname}*  
* [Publish Message]  
*rostopic pub {topicname} {MessageType} {Message}*  
###ROS RUN
* [Execution]  
*rosrun {pkgname} {executable}*  
###ROS CD
* [Go to pkg's Location]  
*roscd {pkgname}*  
###ROS Launch
### Make Workspace and Compile Package
* [Create Workspace directory]  
*mkdir -p {workspace}*  
*cd {workspace}*  
*catkin_make*  
*catkin_create_pkg {pkgname} rospy {lang}*  
*cd {workspace/devel/}*   
*source setup.bash*  
*mkdir {pkgname}/launch*  
*touch {topicname}.launch*  
*gedit .*  

#XML
 <node name="hahahh" pkg="turtlesim" type="turtlesim_node" />  


* [BAIDU](http://www.baidu.com)
