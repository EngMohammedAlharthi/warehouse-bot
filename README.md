# Robot Arm Project - Warehouse Automation

## Overview
This project includes the design and motion logic of a robotic arm intended for automating tasks inside a warehouse. The robot is designed to perform object pickup and placement without any human input, based on a defined motion algorithm and working area.

## Project Contents
- 3D model file: Robot Working Envelop Model.stl
- Motion execution algorithm (text-based)
- Working envelope description

## Execution Algorithm
1. Start the robot system
2. Scan the environment for items and storage locations
3. Move the arm to the pickup location
4. Grab the item using the gripper
5. Move the arm to the target drop-off location
6. Release the item
7. Repeat or wait for the next command
8. Stop when the task is complete or manually interrupted

## Working Envelope
Based on the STL model (Robot Working Envelop Model.stl), the robot operates within the following approximate range:

- Horizontal reach: around 1.0 meter
- Vertical range: around 0.8 meter
- Depth range: about 0.9 meter
- Motion type: Combination of revolute and prismatic joints
- Estimated shape: cylindrical working space

This range gives a general idea of how far and where the robot arm can move during operation.

## Notes
This repository focuses on the robot's structure and logic. It does not include physical hardware or full control code, but it provides a solid base for building or simulating the system.
