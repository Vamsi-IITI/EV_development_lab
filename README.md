# EV_development_lab
A Gazebo world depicting a typical Electric Vehicle developement lab equipped with AGVs.

## Instructions :

1. Open Terminal and run ``` git clone https://github.com/Vamsi-IITI/EV_development_lab.git ```
2. ``` cd EV_development_lab/ ```
3. ``` cd winter/myrobot/ ```
4. ``` mkdir build ```
5. ``` cd build/```
6. ``` cmake ../ ```
7. ``` make ```
8. ``` export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/EV_development_lab/winter/myrobot/build ```  (enter path of build directory in your system)
9. ``` cd .. ```
10. ``` cd world ```
11. ``` gazebo EV_development_lab.world ```

