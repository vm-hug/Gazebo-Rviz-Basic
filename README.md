MÔ PHỎNG CÁNH TAY 6 KHỚP TRÊN GAZEBO & RVIZ

Bước 1: Biên dịch lại (để chắc chắn ROS đăng ký gói mới)
cd catkin_ws
catkin_make

Bước 2: Nạp môi trường (Bước quan trọng nhất)
source devel/setup.bash

Bước 3: Chạy lại lệnh Launch
roslaunch ur5_gazebo ur5_world.launch
