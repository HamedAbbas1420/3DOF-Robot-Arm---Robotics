/*
By: Eng. Hamed Abbas Abd El Halim - Mechatronics Engineer.
mail: hamed.abbas9922@gmail.com

This is application project mainly on Robotics inverse kinematics.
3R (3 revolute joints): Base, Shoulder and Elbow. you can add end effector if you want, i did not use end effector gripper.
inverse kinematics approach: How to make the end effector reach specific position?
 Using end effector position to get joint angles required to reach this position

make sure to operate the servo motors as described in the datasheet, 
here i am using 3 Mg995 servo motors whch operate with in 4.8v - 7.2volts and require about 1amp/each motor
for servo motor powering, you can use one of these:
1) Two 18650 li batteries in series(2*3.7=7.4v) entering to a buck converter circuit (MUST, not to damage servo motors)
2) Your PC USB cable (not recommended if you load on servo motors)

Microcontroller: Arduino Uno


*/