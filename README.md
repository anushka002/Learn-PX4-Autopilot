# Learn-PX4-Autopilot

# PX4 Autopilot Drone Simulation - Beginner Course

Welcome to the **PX4 Autopilot Drone Simulation Beginner Course**! This repository is designed to help you get started with simulating a drone using the PX4 Autopilot software. Whether you're new to drones or software simulation, this guide will walk you through the basics in a simple and friendly way.

![image](https://github.com/user-attachments/assets/c6a9612b-9817-4af2-861d-b3f1ef637fe2)


## What is PX4 Autopilot?
PX4 is an open-source flight control software used for drones and other unmanned vehicles. With PX4, you can simulate a drone's behavior in a virtual environment before testing it in the real world.

## Goal of This Course
In this beginner course, you'll learn how to:
- Set up a PX4 simulation environment.
- Run a basic drone simulation.
- Explore the tools and features of PX4.


This is the first step in a scalable learning journey—more advanced topics can be added later!

## Prerequisites
Before you begin, make sure you have:
- A computer (Windows, macOS, or Linux).
- Basic familiarity with using a terminal or command line.
- A curiosity to learn about drones!

## Getting Started
Follow these steps to set up and run your first PX4 drone simulation:

### 1. Install Required Software
- **Git**: To clone this repository. [Download Git](https://git-scm.com/downloads).
- **PX4 Firmware**: We’ll use the PX4 source code. Instructions below.
- **Gazebo Simulator**: A simulation tool for drones. Comes with PX4 setup.
- **QGroundControl**: A ground station app to monitor your drone. [Download QGroundControl](https://docs.qgroundcontrol.com/master/en/getting_started/download_and_install.html).

### 2. Clone This Repository
Open your terminal and run:
```bash
git clone https://github.com/anushka002/Learn-PX4-Autopilot.git
```
### 3. Set Up PX4 Firmware (Already Present in Repo)
Install dependencies (Ubuntu example):
```
cd Learn-PX4-Autopilot/PX4-Autopilot
bash ./Tools/setup/ubuntu.sh
```
(For Windows or macOS, check the [official PX4 docs](https://docs.px4.io/main/en/dev_setup/dev_env.html))

### 4. Run Your First Simulation
In the PX4-Autopilot folder, start the simulation:
```
make px4_sitl gazebo
```
Open QGroundControl to see your virtual drone in action!
```
cd path-to-QGroundControl app image file
chmod +x QGroundControl.AppImage
./QGroundControl.AppImage
```
---
### What’s Next?

Try flying the drone in the simulator using QGroundControl.
Check out the /docs folder in this repo (coming soon!) for more guides.

---
### Resources
[PX4 Official Documentation](https://docs.px4.io/main/en/)

Happy simulating! 🚁
