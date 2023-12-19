# Pushbot
This is a repository of Blocks programs for the Pushbot demonstration robot. 

This is a FIRST Tech Challenge robot used for demonstrations of hardware and programming. The robot using Tetrix parts. 
- two old AndyMark NeveRest Classic 40 gearmotors mounted on the rear wheels;
- motor encoder cables connecting each motor to the control hub (including Rev Logic Level Converters);
- 4" tetrix wheels on the rear;
- 4" omni-wheels on the front;
- a Rev Control Hub and battery;
- a Logitech C270 webcam.

For the CENTERSTAGE game a "plow" was added to the front that let's the robot push pixels onto the spike marks.

![Model](https://raw.githubusercontent.com/acharraggi/Pushbot/main/Images/PXL_20231203_191218559.jpg)

 The **.blk** files listed above are the Blocks programs that you can run on your robot if the configuration file is the same. This robot has two motors **left_drive** and **right_drive** and a webcam called **webcam 1**. The motors on this robot are configured as AndyMark NeveRest Classic 40 Gearmotors, your config file should have the motors set to whatever motors you are using for your robot. 

 The following programs are on the Pushbot. Click on the program names below to see the downloaded PNG image of the program.

- [RobotAutoDriveByGyro_Blocks](Images/RobotAutoDriveByGyro_Blocks.png) - this is a Blocks copy of the [RobotAutoDriveByGyro_Linear.java](https://github.com/FIRST-Tech-Challenge/FtcRobotController/blob/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples/RobotAutoDriveByGyro_Linear.java) sample program. It makes use of motor encoders and the Rev Control Hub IMU for more accurate driving and turning. See the robot driving using the [RobotAutoDriveByGyro_Blocks program on YouTube](https://youtu.be/8sitKrHBNyY). See also the tutorial webpage on the [RobotAutoDriveByGyro_Blocks program](https://firstroboticsbc.org/ftc/ftc-team-resources/RobotAutoDriveByGyro_Blocks/). <br/> &nbsp;
- [RobotAutoDriveByGyro_Demo](Images/RobotAutoDriveByGyro_Demo.png) - this is a copy of the RobotAutoDriveByGyro_Blocks program that uses the same driving functions to move the robot around the Centerstage field. See the robot using the [RobotAutoDriveByGyro_Demo program on YouTube.](https://youtu.be/-TFp3KY9alM)