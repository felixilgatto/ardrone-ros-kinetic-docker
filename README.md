# ardrone-ros-kinetic-docker
Docker environment with Gazebo 7 and ros kinetic for ardrone communication and simulation

## Content
ros kinetic and gazebo 7
package : [ardrone_autonomy](https://github.com/AutonomyLab/ardrone_autonomy), [tum_simulator kinetic rework](https://github.com/angelsantamaria/tum_simulator),
[custom package](https://github.com/felixcapuano/ardrone-facetracker)

This docker is inspired by https://github.com/SoftArch/racecar-gazebo

## Requirement

Make sure [docker](https://docs.docker.com/get-docker/) is installed and is running.

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
```bash
# use : Ctrl + C
# then
docker-compose down
```

## Usage

First open new command prompt and run the ros core :
```bash
roscore
```

To emulate the ardrone you can launch the gazebo simulation using in a command prompt:
```bash
roslaunch cvg_sim_gazebo ardrone_testworld.launch
```

To pilote the drone you can use this documentation frome ardrone autonomy:

- https://ardrone-autonomy.readthedocs.io/en/latest/reading.html
- https://ardrone-autonomy.readthedocs.io/en/latest/commands.html

# By
felix
