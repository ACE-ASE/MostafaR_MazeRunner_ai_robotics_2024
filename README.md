# MazeRunner_ai_robotics_2024

## Project Description

MazeRunner is a project aimed at implementing Deep Reinforcement Learning (DRL) for autonomous maze navigation and Convolutional Neural Networks (CNN) for image recognition. The objective is to develop an AI-powered robot capable of navigating through a maze to reach a goal in a specific order.

### Goal

The main goal of this project is to create an autonomous robot that can successfully navigate through a maze to reach a goal while recognizing the order of the goal using image recognition.

### Approach

1. **Deep Reinforcement Learning (DRL)**:

   - The robot will learn to navigate the maze using DRL techniques. DRL allows the robot to learn optimal actions by interacting with the environment.
   - Similar to quiz 3, where a car navigates towards a goal, here the robot will navigate towards the goal in the maze.

2. **Convolutional Neural Networks (CNN)**:

   - CNN will be used for image recognition to determine the order of the goal.
   - The robot will take an image of the goal and use CNN to recognize the number associated with the goal's order.

3. **Maze Environment**:
   - The maze environment will be constructed with walls and obstacles.
   - The maze may vary in complexity to challenge the robot's navigation capabilities.

## Implementation

The implementation of MazeRunner will involve several steps:

1. **Environment Setup**:

   - Creation of a simulated maze environment using suitable software (e.g., Pygame, Unity, etc.).
   - Designing maze layouts with walls and obstacles.

2. **Deep Reinforcement Learning**:

   - Implementing a DRL algorithm (e.g., Q-learning, Deep Q-Networks, etc.) to train the robot for maze navigation.
   - Tuning hyperparameters and training the DRL model on the maze environment.

3. **Image Recognition with CNN**:

   - Developing a CNN architecture for image recognition.
   - Training the CNN model on images of goals to recognize the goal order.
   - Integrating the CNN model with the robot's vision system.

4. **Integration**:
   - Integrating the DRL-based navigation system with the CNN-based image recognition system.
   - Testing the integrated system in the maze environment.

## Usage

To run MazeRunner, follow these steps:

1. **Setup Environment**:

   - Install the necessary dependencies and libraries.
   - "python .\setup.py install"
   - use python 3.12.2 version
   - Set up the maze environment.

2. **Training**:

   - Train the DRL model by running the training script.
   - Train the CNN model for image recognition.

3. **Testing**:
   - Test the trained models in the maze environment to ensure proper navigation and image recognition.

## Contributors

- Pawarat Phatthanaphusakun 13662352
- [Collaborator 1]
- [Collaborator 2]
- [Collaborator 3]

## License

[Insert license information]

## Acknowledgements

[Maze Runner 2D, by Al Sweigart al@inventwithpython.com Maze files are generated by mazemakerrec.py]
