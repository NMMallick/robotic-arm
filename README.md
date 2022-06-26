# robotic-arm
Project proposal to bring new students into the world of robotics. 

Hardware schematics for a triple robot setup:
![RobotArm_v2](https://user-images.githubusercontent.com/44278520/175837966-72ebf749-7c93-4647-9621-246f1a937210.png)

Hardware Notes:
- The 5VEN (5 Volt Enable) on the L298N2 motor driver jumper (represented by green wire) needs to be populated so that the 12V motor power will be used for the 5V logic.
- Arduino power to be supplied by labtop USB. IT IS NOT RECOMMENDED TO HAVE LAPTOP CHARGING WHILE PLUGGED INTO ARDUINO. This will create a ground loop witht he power supply which may affect the performance.
