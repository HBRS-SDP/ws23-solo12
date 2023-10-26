# General Notes for Development

## Introduction

**Problem Description**: The SOLO 12 Quadruped Robot is a powerful robotic platform with complex control requirements. This project aims to create a control abstraction to simplify robot operation and experimentation.

**Project Goals**: Our goal is to design a C++ based abstraction that facilitates communication with simulators, including support for importing URDF models. The abstraction will allow control at a 1 kHz loop frequency, making the SOLO 12 more accessible to developers and researchers.

## Specifications of Collected Requirements (User Stories)

- User Story 1: Simulator Integration
    - As a developer, I want to establish communication with a simulator for testing and development.
    - Acceptance Criteria: The abstraction should interface seamlessly with a simulator, such as Gazebo, for testing and validation.
- User Story 2: URDF Import
    - As a developer, I want to import a URDF model of the SOLO 12 into the simulator.
    - Acceptance Criteria: The abstraction should support the accurate import of a URDF model to represent the robot's physical characteristics and kinematics.

- User Story 3: C++ Control Software
    - As a developer, I want a C++ control software framework to manage the robot's behavior.
    - Acceptance Criteria: The control software should be developed in C++ and provide a foundation for controlling the SOLO 12 in real-time.
- User Story 4: Control Loop Frequency
    - As a developer, I want to implement a control loop with a frequency of 1 kHz for precise and real-time control.
    - Acceptance Criteria: The abstraction should meet the 1 kHz control loop frequency requirement.

- User Story 5: Abstraction API
    - As a developer, I want a well-defined API for controlling the SOLO 12, including gait control, sensing, teleoperation, and safety features.
    - Acceptance Criteria: The abstraction should provide an API that is easy to use and understand.
- User Story 6: Safety and Testing
    - As a user, I want safety features and thorough testing to ensure secure robot operation.
    - Acceptance Criteria: The abstraction should include safety mechanisms and undergo rigorous testing for reliability

## Development Tools & Technologies

- C++ and Python: We will utilize C++ & Python for robust and real-time control software development.
- Gazebo: Gazebo will serve as our simulation environment for testing and validation.
- ROS (Robot Operating System): ROS will be used as a framework for managing communication between components.
- Git: Git and platforms like GitHub will be employed for version control and collaboration.
