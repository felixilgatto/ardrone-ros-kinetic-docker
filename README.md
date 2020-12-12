# ardrone-ros-kinetic-docker
Docker environment with Gazebo 7 and ros kinetic for ardrone communication and simulation

## Content
ros kinetic and gazebo 7
package : [ardrone_autonomy](https://github.com/AutonomyLab/ardrone_autonomy), [tum_simulator kinetic rework](https://github.com/angelsantamaria/tum_simulator),
[custom package](https://github.com/felixcapuano/ardrone-facetracker)
docker inspired by https://github.com/SoftArch/racecar-gazebo

## Installation
Simply run :
```bash
git clone https://github.com/felixcapuano/ardrone-ros-kinetic-docker
cd ./ardrone-ros-kinetic-docker
docker-compose up
```

Tadam !!!
The new environment can be access on this port :
http://localhost:6080/


To stop the docker:
```bash*
# use : Ctrl + C
# then
docker-compose down
```

# By
felix