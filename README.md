
# LAB 02

## Part 1: Oculus Integration - HandsInteractionTrainScene

This repository contains a modification of the HandsInteractionTrainScene as part of the Oculus integration. In Part 1, I made the following changes:

#### Button Duplication

I duplicated two buttons within the HandsInteractionTrainScene.

#### Implemented Behaviors

#### Color Change Behavior

I added a behavior that allows me to change the color of four cactus to red. When I press the associated button, these cactus change color.

#### SuperSpeed Behavior

Another behavior I implemented enables the drone to move at a significantly faster pace. Each time I press the corresponding button, the drone's speed increases.

#### Button Integration

To activate these behaviors, I connected them to the duplicated buttons through the Interactable state change unity events.

Feel free to explore the repository for the modified scene and associated scripts.



## Part 2: Drone and Camera Controls

### Overview

In Part 2 of my course assignment, I conducted reviews of three different APK projects for the Oculus Quest 2, created by Omang, Abhishek, and Parinda. Following these reviews, I proceeded to integrate specific behaviors for both the drone and the user's perspective (camera) controls based on my personal preferences and observations.

#### Omang's Drone Project

Omang's project showcased a control scheme where the Right Thumb Stick was utilized to maneuver the drone, which closely aligned with my own design choice. What particularly impressed me was Omang's implementation of a feature where clicking the Right Thumb Stick Button enabled additional control of the Thumb Stick for lateral movement, enhancing the overall maneuverability of the drone. Omang also assigned the right Index button press for the laser function. While effective, I believe that placing laser controls near the thumb could enhance the gaming experience.

#### Abhishek's Drone Project

Abhishek's project displayed several positive aspects but also had some issues. One significant drawback was the inconsistency in turning the drone left using the right thumb button; it required multiple presses to achieve the desired effect. However, Abhishek's approach to camera perspective was intriguing and offered a fresh perspective on the control scheme.

#### Parinda's Drone Project

Parinda's project exhibited certain shortcomings, primarily the inability to turn the drone left or right using the controller. Additionally, incorporating a dedicated button for toggling the laser could have improved user-friendliness.

### Chosen Controls

For my project, I carefully selected controls based on both my preferences and the feedback I gathered:

##### Drone Controls

- **Move Forward**: Right Thumb Stick Forward() - I opted for the right thumbstick for drone movement to keep the left thumbstick for camera control. This allows for smoother drone navigation.
- **Move Backward**: Right Thumb Stick Backward()
- **Move Right**: A Button Press() - I chose this button for ease of use and to provide precise control over rightward movement.
- **Move Left**: B Button Press() - Similar to the move right control, I selected the B button for leftward movement for ease of use and precision.
- **Turn Left**: Right Thumb Stick Right() - This felt more intuitive for turning left.
- **Turn Right**: Right Thumb Stick Left() - This felt more intuitive for turning right.
- **Turn Laser On**: Right Thumb Stick Button - I assigned an important function like turning the laser on to this button for quick access.
- **Turn Laser Off**: Left Thumb Stick Button - Similar to turning the laser on, I placed the laser off function on the left thumbstick button for quick access.

##### Camera (User) Controls

- **Move Forward**: Left Thumb Stick Forward() - To maintain consistency, I used the left thumbstick for camera forward movement.
- **Move Backward**: Left Thumb Stick Backward()
- **Move Right**: Left Thumb Stick Right()
- **Move Left**: Left Thumb Stick Left()
