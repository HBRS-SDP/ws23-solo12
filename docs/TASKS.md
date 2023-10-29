# Project Activities:

## Software Architecture Design

- [ ] Define the components of the C++ software architecture.
    - [ ] Identify core modules and their responsibilities.
    - [ ] Determine component interactions.
- [ ] Create a class diagram illustrating the relationships between these components.
    - [ ] Design the class diagram.
    - [ ] Define class hierarchies and attributes.
- [ ] Decide on the C++ libraries and frameworks to be used.
    - [ ] Research potential C++ libraries and frameworks.
    - [ ] Evaluate pros and cons.
    - [ ] Make a final decision on library and framework selection.

## Gazebo Robot Model

- [ ] Design and build 3D models for the robot's physical components.
- [ ] Create C++ classes or structures for robot joints and sensors.
- [ ] Implement the robot's URDF in C++. (is not necessary, urdf is a completely independent language from c++ and they are not related so this is not necessary.)

## API Implementation

- [ ] Define the C++ classes and methods for the API in detail.
    - [ ] Create a comprehensive list of API methods.
    - [ ] Document the purpose and expected behavior of each method.
    - [ ] Define parameters and return types.
- [ ] Create the C++ header files and source code for the API classes.
    - [ ] Set up directory structure for API files.
    - [ ] Create header files (.h) with class declarations.
    - [ ] Implement source files (.cpp) with method stubs and comments.
- [ ] Implement the core functionality of each C++ API method.
    - [ ] Implement a single, simple API method as a prototype.
    - [ ] Test the method in isolation.
    - [ ] Gradually implement the remaining API methods, testing and documenting each one.

## Unit Testing

- [ ] Write C++ unit tests for each API method using testing frameworks like Google Test.
- [ ] Implement test cases to cover different input scenarios.
- [ ] Set up a continuous integration system to run C++ tests automatically.

## Integration Testing

- [ ] Design integration tests that simulate interactions between the C++ API and the Gazebo simulation.
- [ ] Implement C++ test cases for the integration tests.
- [ ] Create a test environment to automate integration testing, including handling C++ components.

## Documentation

- [ ] Create a README file with an overview of the project and C++ installation instructions.
- [ ] Write detailed C++ API documentation for each class and method.
- [ ] Include C++ code examples and usage samples in the documentation.

## ~User Interface (UI)~ (TBD)

- [ ] Design the user interface layout and interactions in C++.
- [ ] Implement the C++ UI using relevant C++ GUI libraries like Qt or SDL.
- [ ] Integrate the C++ UI with the API for real-time control.

## Safety Features

- [ ] Define safety rules and constraints for robot operation in C++.
- [ ] Implement safety checks in the C++ API to prevent unsafe actions.
- [ ] Create an emergency stop mechanism for both the virtual and physical robots, using C++.

## ~Data Logging and Analysis~ (TBD)

- [ ] Set up a data logging system in C++ to capture robot performance data.
- [ ] Develop C++ tools for analyzing the logged data and generating reports.
- [ ] Implement real-time monitoring of critical data in C++.

## ~Deployment and Scaling~ (TBD)

- [ ] Plan the deployment strategy for the C++ project, considering platform compatibility.
- [ ] Consider scalability options for handling a growing number of robots in C++.
- [ ] Document deployment procedures and configurations in the context of C++ development.

## Error Handling and Recovery (extra):

- [ ] Identify potential error scenarios in the C++ project.
- [ ] Implement error-handling code for each scenario in C++.
- [ ] Develop recovery procedures in C++ to gracefully handle errors and resume normal operation.
