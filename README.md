
# LAB 02

## Part 1: Oculus Integration - HandsInteractionTrainScene

This repository contains a modification of the HandsInteractionTrainScene as part of the Oculus integration. In Part 1, I made the following changes:

## Button Duplication

I duplicated two buttons within the HandsInteractionTrainScene.

## Implemented Behaviors

### Color Change Behavior

I added a behavior that allows me to change the color of four cacti to red. When I press the associated button, these cacti change color.

### SuperSpeed Behavior

Another behavior I implemented enables the drone to move at a significantly faster pace. Each time I press the corresponding button, the drone's speed increases.

## Button Integration

To activate these behaviors, I connected them to the duplicated buttons through the Interactable state change unity events.

Feel free to explore the repository for the modified scene and associated scripts.



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
