# Line_Follower_and_Obstacle_Avoiding_Tank

## 1. Introduction
In this project, we have created a line-following tank that is capable of avoiding obstacles, using an Arduino-based platform (RoMeo BLE v1.0). This tank utilizes infrared sensors to detect a black line on the ground (not magnetic tape) and follows it. Additionally, it employs ultrasonic sensors to identify obstacles and navigate around them. The robot can operate in complete darkness and is able to rejoin the main dark line even if there are other misleading lines present after avoiding an obstacle. Furthermore, if the line is broken while moving forward, it can also find its way back to the path.

Click to see the demonstration video below!!

<a href="https://www.youtube.com/shorts/7qLS-UVV_zI" target="_blank" rel="noopener noreferrer"><img src="http://img.youtube.com/vi/7qLS-UVV_zI/hqdefault.jpg" alt="Watch the video" style="max-width:100%;"></a>


## 2. Hardware Components
![Tank Image](https://raw.githubusercontent.com/Tamago55/Line-Follower-Obstacle-Avoiding/main/pic/tank.JPG)
- [RoMeo BLE v1.0](https://wiki.dfrobot.com/RoMeo_BLE__SKU_DFR0305_)
- Devastator Tank Mobile Platform
- Ultrasonic Sensor
- Mini Servo Motor
- 3 Channel IR Sensor

## 3. Software 
- PlatformIO with Visual Studio Code

## 4. Logic
### Obstacle Avoidance
![Obstacle Avoidance Logic Image](https://raw.githubusercontent.com/Tamago55/Line-Follower-Obstacle-Avoiding/main/pic/step1.png)
### Line Detection
![Line Detection Logic Image](https://raw.githubusercontent.com/Tamago55/Line-Follower-Obstacle-Avoiding/main/pic/step2.png)
### Combine Object Avoidance and Line Detection
![Combined Logic Image](https://raw.githubusercontent.com/Tamago55/Line-Follower-Obstacle-Avoiding/main/pic/step3.png)

