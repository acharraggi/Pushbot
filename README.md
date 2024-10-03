# Pushbot
This is a repository of Blocks programs for the Pushbot demonstration robot. Many of these programs are copies of Java sample programs from the SDK converted into Blocks.

This is a *FIRST* Tech Challenge robot used for demonstrations of hardware and programming. The robot using Tetrix parts. 
- two old AndyMark NeveRest Classic 40 gearmotors mounted on the rear wheels;
- motor encoder cables connecting each motor to the control hub (including Rev Logic Level Converters);
- 4" tetrix wheels on the rear;
- 4" omni-wheels on the front;
- a Rev Control Hub and battery;
- a Logitech C920 webcam, that replaced the C270 webcam;
- a Rev Color Sensor V3.

For the CENTERSTAGE game a "plow" was added to the front that let's the robot push pixels onto the spike marks.
For the INTO THE DEEP game the plow was modified to hold a sample that could be pushed into the net zone.

![Model](https://raw.githubusercontent.com/acharraggi/Pushbot/main/Images/pushbot.png)

 The **.blk** files listed above are the Blocks programs that you can run on your robot if the configuration file is the same. This robot has two motors **left_drive** and **right_drive** and a webcam called **webcam 1**. The motors on this robot are configured as AndyMark NeveRest Classic 40 Gearmotors, your config file should have the motors set to whatever motors you are using for your robot. 

 The following programs are on the Pushbot. Click on the program names below to see the downloaded PNG image of the program.

Programs for the INTO THE DEEP season

- [DeepAuto1](Images/DeepAuto1.png) - This is a simple program to drive forward for 1 second and stop. It can be used to push samples into the net zone or park in the observation zone. It's based on the RobotAutoDriveByTime sample. See the tutorial webpage at [DeepAuto1](https://firstroboticsbc.org/ftc/ftc-team-resources/intothedeep-my-first-autonomous-program/).

- [DeepAuto2](Images/DeepAuto2.png) - This is a simple program to place a sample in the net zone and park in the observation zone. It contains basic code for moving using motor encoders and turning using the control hub IMU. See the tutorial webpage at [DeepAuto2](https://firstroboticsbc.org/ftc/ftc-team-resources/intothedeep-my-second-autonomous-program/).

- [DeepAutoAscend3](Images/DeepAutoAscend3.png) - This is a complex program that pushes three samples into the net zone and does a level one acent. It uses the functions from the RobotAutoDrivesByGyro program to drive and turn. See the tutorial webpage at [DeepAuto2](https://firstroboticsbc.org/ftc/ftc-team-resources/DeepAutoAscend3/).

 The following Robot Auto Drive programs are included as sample Blocks programs as of the INTO THE DEEP season. You can create them directly on your robot without having to download them here.

- [RobotAutoDriveByGyro_Blocks](Images/RobotAutoDriveByGyro_Blocks.png) - this is a Blocks copy of the [RobotAutoDriveByGyro_Linear.java](https://github.com/FIRST-Tech-Challenge/FtcRobotController/blob/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples/RobotAutoDriveByGyro_Linear.java) sample program. It makes use of motor encoders and the Rev Control Hub IMU for more accurate driving and turning. See the robot driving using the [RobotAutoDriveByGyro_Blocks program on YouTube](https://youtu.be/8sitKrHBNyY). See also the tutorial webpage on the [RobotAutoDriveByGyro_Blocks program](https://firstroboticsbc.org/ftc/ftc-team-resources/RobotAutoDriveByGyro_Blocks/).

- [RobotAutoDriveByGyro_Demo](Images/RobotAutoDriveByGyro_Demo.png) - this is a copy of the RobotAutoDriveByGyro_Linear.java program that uses the same driving functions to move the robot around the Centerstage field. See the robot using the [RobotAutoDriveByGyro_Demo program on YouTube.](https://youtu.be/-TFp3KY9alM).

- [RobotAutoDriveByTime_Blocks](Images/RobotAutoDriveByTime_Blocks.png) - this is a copy of the [RobotAutoDriveByTime_Linear.java](https://github.com/FIRST-Tech-Challenge/FtcRobotController/blob/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples/RobotAutoDriveByTime_Linear.java) sample program. This OpMode illustrates the concept of driving a path based on time. See the robot using the [RobotAutoDriveByTime_Blocks program on YouTube.](https://youtu.be/mrhTzFVS_Is). See also the tutorial webpage on the [RobotAutoDriveByTime_Blocks sample program](https://firstroboticsbc.org/ftc/ftc-team-resources/RobotAutoDriveByTime_Blocks/).

- [RobotAutoDriveToAprilTagTank_Blocks](Images/RobotAutoDriveToAprilTagTank_Blocks.png) - this is a Blocks copy of the [RobotAutoDriveToAprilTagTank.java](https://github.com/FIRST-Tech-Challenge/FtcRobotController/blob/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples/RobotAutoDriveToAprilTagTank.java) sample program. It makes use of motor encoders and the Rev Control Hub IMU for more accurate driving and turning. See the robot driving using the [RobotAutoDriveToAprilTagTank_Blocks program on YouTube](https://youtu.be/Z32eKDitKmo). See also the tutorial webpage on the [RobotAutoDriveToAprilTagTank_Blocks sample program](https://firstroboticsbc.org/ftc/ftc-team-resources/RobotAutoDriveToAprilTagTank_Blocks/).

- [RobotAutoDriveToLine_Blocks](Images/RobotAutoDriveToLine_Blocks.png) - this is a copy of the [RobotAutoDriveToLine_Blocks.java](https://github.com/FIRST-Tech-Challenge/FtcRobotController/blob/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples/RobotAutoDriveToLine_Linear.java) sample program. This OpMode illustrates the concept of driving up to a line and then stopping. See the robot using the [RobotAutoDriveToLine_Blocks program on YouTube.](https://youtu.be/-MpNI2-azjw). See also the tutorial webpage on the [RobotAutoDriveToLine_Blocks sample program](https://firstroboticsbc.org/ftc/ftc-team-resources/RobotAutoDriveToLine_Blocks/).

- [SensorIMUOrthogonal_Blocks](Images/SensorIMUOrthogonal_Blocks.png) - this is a Blocks copy of the [SensorIMUOrthogonal.java](https://github.com/FIRST-Tech-Challenge/FtcRobotController/blob/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples/SensorIMUOrthogonal.java) sample program. The program makes use of the Rev Control Hub IMU and shows orientation and and angular velocities on the driver station.  See also the tutorial webpage on the [SensorIMUOrthogonal_Blocks program](https://firstroboticsbc.org/ftc/ftc-team-resources/SensorIMUOrthogonal_Blocks/).

- [TFOD-prop-April-Tag](Images/TFOD-prop-April-Tag.png) - This is a CENTERSTAGE autonomous program that uses TensorFlow to detect a Team Prop from the starting position, places the purple pixel, and then lines up on the correct backdrop area using April Tags. See the robot using the [TFOD-prop-April-Tag program on YouTube.](https://youtu.be/ko0mzQYXO2E). See also the tutorial webpage on the [TFOD-prop-April-Tags autonomous program](https://firstroboticsbc.org/ftc/ftc-team-resources/centerstage-tfod-prop-april-tag-autonomous-program/).
