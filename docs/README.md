# General Notes for Development


Project title: Abstraction for Controlling the SOLO 12 Quadruped Robot

## Introduction

**Problem Description**: The SOLO 12 Quadruped Robot is a powerful robotic platform with complex control requirements. This project aims to create a control abstraction to simplify robot operation and experimentation.

**Project Goals**: Our goal is to design a C++ based abstraction that facilitates communication with simulators, including support for importing URDF models. The abstraction will allow control at a 500 Hz loop frequency, making the SOLO 12 more accessible to developers and researchers.

## Specifications of Collected Requirements (User Stories)

1. **User Story:** As a robotics engineer, I want to be able to initialize communication with the SOLO 12 robot in both simulation and on the real robot using a common API, so that I can streamline development and testing across both environments.
- **Acceptance Criteria:**
   - The API should provide a function to establish communication with the SOLO 12 in both simulation and on the real robot.
   - The API should support specifying the robot's network interface for communication.

2. **User Story:** As a developer, I want to import a URDF model of the SOLO 12 into the simulator.
- **Acceptance Criteria**:
    - The abstraction should support the import of a URDF model to represent the robot's physical characteristics and kinematics.

3. **User Story:** As a robot developer, I want the common API to provide low-level control command for speed, position and effort in all joins of the robot in simulation and on the real robot.
- **Acceptance Criteria:**
   - The API should offer functions to write speed, position, effort commands.

4. **User Story**: As a developer, I want to implement a control loop with a frequency of 500 Hz for precise and real-time control.
- **Acceptance Criteria**:
    - The abstraction should meet the 500 Hz control loop frequency requirement.

5. **User Story:** As a software developer, I want the common API to be developed in C++ to facilitate smooth interoperability between simulation and real
- **Acceptance Criteria:**
   - The API should be implemented in C++ and optionally provide Python bindings. 
   - Clear and well-documented API should be provided to enable developers to use the API effectively.
   - The API documentation should include clear usage instructions, code samples, and examples to help users understand how to control the SOLO 12 robot.

6. **User Story:** As a robotics researcher, I want the common API to abstract the underlying communication details, ensuring that other robot software components (e.g., control, perception) can interact with the robot agnostically, simplifying development and maintenance.
- **Acceptance Criteria:**
   - The API should hide low-level communication details, providing a high-level, user-friendly interface.

7. **User Story:** As a collaborator, I want the project to be well-documented, version-controlled, and hosted on a platform like GitHub for ease of access and collaboration with other developers.
- **Acceptance Criteria:**
   - The project should be hosted on a version control platform (e.g., GitHub) with clear version history.
   - Detailed project documentation should be available on the repository to provide information on installation, usage, and development guidelines.

8. **User Story**: As a user, I want safety features and thorough testing to ensure secure robot operation.
- **Acceptance Criteria**:
    - The abstraction should include safety mechanisms, such as limit threshold detection and emergency stop procedures, and undergo rigorous testing for reliability and fault tolerance.

## Development Tools & Technologies

- C++ and Python: We will utilize C++ & Python for robust and real-time control software development.
- Gazebo: Gazebo will serve as our simulation environment for testing and validation.
- ROS (Robot Operating System): ROS will be used as a framework for managing communication between components.
- Git: Git and platforms like GitHub will be employed for version control and collaboration.


