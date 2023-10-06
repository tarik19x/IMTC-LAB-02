
# Unity Drone Control Project

## Overview

This repository contains my Unity project that demonstrates drone control using Oculus controllers. The project is divided into two parts: Part 1 involves duplicating and adding behaviors to buttons in the HandsInteractionTrainScene, and Part 2 focuses on implementing specific behaviors for the drone and camera controls.

## Part 1: HandsInteractionTrainScene

In this part, I duplicated and added behaviors to buttons in the HandsInteractionTrainScene. The buttons and their associated actions are as follows:

- **A Button**: Used for interacting with objects.
- **B Button**: Used for menu interactions.
- **Left Thumb Stick**: Used for locomotion and movement.
- **Right Thumb Stick**: Used for locomotion and movement.

## Part 2: Drone and Camera Controls

In Part 2, I integrated specific behaviors for both the drone and the user's perspective (camera) controls. Here are the chosen controls and the reasoning behind them:

### Drone Controls

- **Move Forward**: Right Thumb Stick Forward() - I opted for the right thumbstick for drone movement to keep the left thumbstick for camera control. This allows for smoother drone navigation.
- **Move Backward**: Right Thumb Stick Backward()
- **Move Right**: A Button Press() - I chose this button for ease of use and to provide precise control over rightward movement.
- **Move Left**: B Button Press() - Similar to the move right control, I selected the B button for leftward movement for ease of use and precision.
- **Turn Left**: Right Thumb Stick Right() - This felt more intuitive for turning left.
- **Turn Right**: Right Thumb Stick Left() - This felt more intuitive for turning right.
- **Turn Laser On**: Right Thumb Stick Button - I assigned an important function like turning the laser on to this button for quick access.
- **Turn Laser Off**: Left Thumb Stick Button - Similar to turning the laser on, I placed the laser off function on the left thumbstick button for quick access.

### Camera (User) Controls

- **Move Forward**: Left Thumb Stick Forward() - To maintain consistency, I used the left thumbstick for camera forward movement.
- **Move Backward**: Left Thumb Stick Backward()
- **Move Right**: Left Thumb Stick Right()
- **Move Left**: Left Thumb Stick Left()

## Building and Testing

To test the project, follow these steps:

1. Build the APK files.
2. Upload the APK files to the provided OneDrive directory.
3. Download the APK files onto your Oculus device and install them.
4. Test the different behaviors for both the drone and camera controls.
5. Compare these controls with three other implementations to assess intuitiveness and practicality.

## Documentation of Comparison

In a separate document, I will provide a comparison of the controls used in this project with those of the other three implementations. I will consider factors such as intuitiveness, ease of use, and practicality when comparing the button choices.

## Video Capture

Please refer to the video capture for a visual demonstration of the project's functionalities in both Part 1 and Part 2.

## Repository Structure

- `Assets/`: Contains Unity project assets.
- `Builds/`: Location for APK builds.
- `Documentation/`: Documentation files, including comparisons.
- `VideoCapture/`: Video recordings of project functionality.

Feel free to explore the repository for the Unity project code and additional documentation.

Happy exploring!

```

This version of the README.md file uses "I" instead of "we" to describe the project and its components.
