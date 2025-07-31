# EcoBot
An Autonomous Garbage Manager

This project proposes the development of an autonomous robot, EcoBot, capable of detecting,
classifying, and sorting waste into biodegradable and non-biodegradable categories. It involves the
development of an intelligent robot which is able to navigate through a simulated environment,
identify objects, and perform pick-and-place operations. The robotic system is designed with the
combination of a mobile robot (Husky) and a robotic arm (KUKA). The implementation of the
simulation environment was done using the PyBullet engine, which provides a realistic setting
used for testing and development.


The aim of this project is to create a robotic solution capable of collecting and identifying objects
efficiently within an environment. The system makes use of pathfinding algorithms for navigation,
such as A-star and leverages computer vision models such as YOLO (You Only Look Once) for
object detection. The combination of both these advanced technologies help in creating an
autonomous garbage manager.
Key components of the project include:
1. Simulation Environment: The project is built using PyBullet creating the environment in
which the robot and objects interact. This includes creating the boundaries, placing the
objects as well as setting up the robot.
2. Robotic Control: The Husky robot is responsible for navigating the environment, while
the KUKA arm performs the manipulation tasks. The control system is designed to
ensure smooth and accurate movements, which enables the robot to interact with objects
well.
3. Pathfinding and Navigation: The A star algorithm is implemented to calculate the shortest
path from the current location to the final or target locations while avoiding obstacles.
This helps in navigating through maze-like environments efficiently.
4. Object Detection and Manipulation: The system uses a YOLO model to detect objects in
real-time through a camera feed from the end effector. Once the object is detected, the
robotic arm is set to pick up the objects and place them in specified bins that are
provided

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/poker-ai.git
cd EcoBot

Install dependencies:

pip install -r requirements.txt

Run the simulation with:

python GarbageCollector.py
