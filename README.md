# waveshare_ugv_study
study notes for waveshare ugv beast.


## To build the ROS image:
docker pull dudulrx0601/ugv_rpi_ros_humble 
git clone git@github.com:waveshareteam/ugv_ws.git


docker run -it -v /home/ws/ugv_ws:/home/ws/ugv_ws --rm dudulrx0601/ugv_rpi_ros_humble:ugv_rpi_ros_humble /bin/bash
apt update
apt install vim iputils-ping iproute2

cd /home/ws/ugv_ws/
. build_first.sh

issue: cannot ping 192.168.2.92?? 
