Dependency
```sh
sudo apt install ros-noetic-dynamixel-sdk
```
 ```sh
sudo apt install ros-noetic-hector-mapping
```
 ```sh
sudo apt install ros-noetic-gmapping
```
 ```sh
sudo apt install ros-noetic-scan-tools
``` 
```sh
sudo apt install ros-noetic-joy
```

Testing
```sh
rostopic pub -r 10 /cmd_vel geometry_msgs/Twist "linear:
  x: 1.0
  y: 0.0
  z: 0.0
angular:
  x: 0.0
  y: 0.0
  z: 0.0"
```
```sh
rostopic pub /cmd_vel geometry_msgs/Twist "linear:
  x: 0.0
  y: 0.0
  z: 0.0
angular:
  x: 0.0
  y: 0.0
  z: 0.0"
```
