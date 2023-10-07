/******************************************************************************
 * Copyright (C) 2023 by Hamed Abbas - Mechatronics Engineer
 *
 * forms is permitted as long as the files maintain this copyright. Users are
 * permitted to modify this and use it to learn about the field of Robotics.
 * Hamed Abbas is not liable for any
 * misuse of this material.
 *
 *****************************************************************************/
/**
 * mail: hamed.abbas9922@gmail.com
 *
 * There is two arduino code files to control the robotic arm:
 * 1. Zero Position: used to bring servo angles into zero position.
 * zero position MUST be defind first - as modelled in robotics kinematics equations - to reach the correct angles
 * to set servo motors to zero position, follow these steps:
 * - Base servo motor: Adjust the motor blade so that the arm points to x-direction of the origin coordinates of the model (Robotics equation folder - 1.jpg)
 * - Shoulder servo motor: Adjust the motor blade so that the first link is parallel to the x-direction
 * - Elbow servo motor: Adjust the motor blade so that the first link is parallel to the second link
 * 
 * 2.Inverse Kinematics
 * in this arduino code file, you can enter the position x, y and z and run the code to reach the end effector target position
 **/
