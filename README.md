# Drone Simulation Tutorial

This repository contains the documentation required to setup and understand the simulation environment.

There are 6 sections so far:

1. **WSL Setup** - For Windows Users to setup the WSL environment required.
2. **Linux Setup** - To configure the Linux environment.
3. **SITL Setup** - To get a Software-In-The-Loop simulated drone up and running.
4. **SITL with Gazebo** - To set up Gazebo as simulation environment.
5. **Controlling the SITL Drone** - Introduces multiple MAVLink libraries that can be used to write programmes to control the drone.
6. **Introduction to ROS** - Optional for those who want to learn ROS and/or MAVROS

The diagram below depicts the simulation software stack:

![Alt text](<docs/Drone Simulation Software Stack with External Programmes.png>)

Basically, the setup is as follows:

* **Section 3 - SITL Setup** runs the Autopilot SITL and the Simulated Drone within a simple simulator (ArduPilot Native Physics Engine).
* **Section 4 - SITL with Gazebo** uses an alternative simulator called Gazebo that is able to perform advanced simulations.
* **Section 5 - Controlling the SITL Drone** talks about how we can create external programmes that can send MAVLink commands to the autopilot to control the simulated drone.
