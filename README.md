### Installation
```
cd ~/ros_catkin_ws/src/
git clone https://github.com/voltbro/ws_serv_B.git
```
### Compilation
```
cd ~/ros_catkin_ws/
sudo ./src/catkin/bin/catkin_make_isolated --install -DCMAKE_BUILD_TYPE=Release --install-space /opt/ros/melodic --pkg=ws_serv_B
```
### Usage

Just run start_configure_B.launch
```
roslaunch ws_serv_B start_configure_B.launch
```
