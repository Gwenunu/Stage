# Utilisation de Gazebo Classic

Nous utilisons Gazebo Classic pour son utilisation facile, la modélisation d'un environnement est plus aisée à prendre
en main que sur les dernières versions de Gazebo.

### Version utilisée : _Gazebo 11.0_
### End of life : _29/01/2025_

### Installation

Liens vers [l'installation de Gazebo Classic](https://classic.gazebosim.org/tutorials?tut=install_ubuntu&cat=install).

## Application au projet

Dans le cadre du développement du robot serveur, il fallait mettre en place une simulation pour simplifier les essais.
Pour cela, dans un terminal avec un workspace sourcé, taper :
    **ros2 launch jetson_robot jetbot.launch.py**

Cela ouvrira l'interface Gazebo, avec le robot et un circuit.

Afin de manoeuvrer le robot, il faut utiliser le noeud *teleop_twist_keyboard*, dans un nouveau terminal, taper
    **ros2 run teleop_twist_keyboard teleop_twist_keyboard**

![Teleop_twist_keyboard](teleop_twist_keyboard.png)

Il est nécessaire d'être sur le terminal executant le noeud teleop_twist_keyboard pour déplacer le robot.

Il est maintenant possible de voir et contrôler le robot sur la simulation.

Ce dernier publie sur les topics des caméras :
    */camera/left*
    */camera/right*
    */cmd_vel*












































































#Liens utiles

##ROS
### DACHING
https://docs.ros.org/en/dashing/index.html
### HUMBLE
https://docs.ros.org/en/humble/index.html
### FOXY
https://docs.ros.org/en/foxy/index.html





##URDF

### GAZEBO
https://automaticaddison.com/how-to-simulate-a-robot-using-gazebo-and-ros-2/

###RVIZ
https://automaticaddison.com/how-to-load-a-urdf-file-into-rviz-ros-2/
https://robotics.snowcron.com/robotics_ros2/nav_improved_create_map.htm
https://robotics.stackexchange.com/questions/96105/how-do-you-load-urdf-files-in-rviz2-with-ros2


###SLAM
https://dev.to/admantium/robot-operating-system-how-to-model-point-cloud-data-in-ros2-aie
https://husarion.com/tutorials/ros2-tutorials/8-slam/




###Erreurs
https://answers.ros.org/question/404052/ros-2-slam-not-working-queue-is-full/
https://answers.ros.org/question/263715/fixed-frame-map-does-not-exist/
https://community.stereolabs.com/t/no-point-cloud-information-is-displayed-in-rviz/952/3
