Process to reproduce error:

1. Open Terminal and execute the following in sequence:
* git clone https://github.com/nice-user1/ros2_acker.git
* cd ros2_acker
* colcon build --symlink-install
* source install/setup.bash
* ros2 launch race_it rsp.launch.py

2. Open another terminal and execute the following in sequence:
* source install/setup.bash
* ros2 run temp_teleop talker

Keep the "temp_teleop talker" window active and control the bot.
