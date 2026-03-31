# Modular Robotic Arm System

![Standalone Arm](images/arm_standalone.png)

## Overview
This project is a modular robotic arm system designed to perform basic manipulation tasks such as gripping and object handling. The arm can operate as a standalone unit or be mounted on a mobile robotic platform, enabling both fixed and mobile manipulation.

The design focuses on flexibility, modularity, and ease of integration with different robotic systems.

## Project Goal
To design a robotic arm that:
- Can function independently as a stationary manipulator
- Can be integrated with a mobile robot chassis
- Provides 4 degrees of freedom for basic manipulation tasks
- Maintains structural simplicity while ensuring functionality

## My Contribution
I designed:
- Complete robotic arm structure
- Joint layout and linkage mechanism
- Servo motor mounting and alignment
- Base mounting system for both standalone and mobile use

## I used models from grabcad for off the shelf components:
- Servo motors 
- Fasteners and standard hardware

## Key Features
- Multi-DOF robotic arm for manipulation tasks
- Dual-mode operation:
  - Standalone configuration
  - Mobile robot-mounted configuration
- Modular mounting base for easy integration
- Lightweight and compact design
- Servo-driven joints for controlled motion

## Design Images

### Standalone Configuration
![Standalone](images/arm_standalone.png)

### Mounted on Mobile Platform
![Mounted](images/arm_mounted.png)

## System Design

### 1. Arm Structure
- Multiple joints driven by servo motors
- Designed for basic pick-and-place operations
- Compact linkage system for efficient motion

### 2. Base Mounting System
- Stable base for standalone operation
- Mounting interface compatible with robot chassis
- Designed to handle load during arm extension

### 3. End Effector (Gripper)
- Simple gripper mechanism for object handling
- Designed for lightweight objects
- Easy to modify for different applications

## Design Considerations
- Stability during arm extension
- Weight distribution when mounted on a mobile base
- Proper alignment of servo axes
- Structural simplicity for easy manufacturing

## Possible Applications
- Pick-and-place tasks
- Educational robotics kits
- Mobile manipulation systems
- Robotics prototyping and experimentation

## Files Included
- CAD source files
- STEP file (universal format)
- Rendered images

## Challenges
- Maintaining stability with extended arm configurations
- Aligning servo motors for smooth motion
- Designing a compact yet functional linkage system
- Ensuring compatibility with both standalone and mobile setups

## Improvements for Next Version
- Add structural reinforcements to reduce flex
- Improve gripper design for better grip strength
- Add cable management for servo wiring
- Optimize joint geometry for increased range of motion
- Integrate feedback sensors (encoders or limit switches)

## Tools Used
- Fusion 360

## Project Status
CAD Design Completed

## Future Work
- Physical prototype development
- Motion control and inverse kinematics implementation
- Vision-based object detection and manipulation

