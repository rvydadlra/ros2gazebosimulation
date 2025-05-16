# ros2gazebosimulation
ROS2 HUMBLE GAZEBO SİMÜLASYON VE KLAVYEDEN HAREKET KONTROLÜ
display launch dosyasıyla çalıştırmak için:
source install/local_setup.bash
 ros2 launch my_first_pkg display.launch.py
gazeboda hareket sağlamak için:
ros2 launch my_first_pkg gazebo.launch.py
ek bir terminalde yukardaki kod çalışırken çalıştırın:
source install/local_setup.bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard
