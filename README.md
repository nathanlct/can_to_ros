# CANSpeedDecoder
Decode CAN messges written in csv file.

### Prerequisites

ROS melodic

## Example
1.Create a ROS Workspace
```
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
```
2.Clone the repo.
```
$ cd ~/catkin_ws/src
$ git clone https://github.com/SafwanElmadani/CANSpeedDecoder.git
```
3.Build the WS
```
$ cd ~/catkin_ws
$ catkin_make
```
4.Source your enviroment:
```
$source ./devel/setup.bash
```
Then use roslaunch to start can_msg_decoder node:
```
$roslaunch can_speed_decoder publish_can_msg.launch file_path:=CAN_Message_.csv
```
The generated bag file should be loacted at ~/.ros directory 
```
$cd ~/.ros
```



