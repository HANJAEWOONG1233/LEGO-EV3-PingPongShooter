# 🏓 EV3 Robot Ping Pong Shooting Project 🤖

## 🎯 Project Overview
The **EV3 Robot Ping Pong Shooting Project** involves designing and programming an autonomous robot based on **LEGO EV3** to execute ping pong matches according to established regulations. This robot is engineered to comply with competition rules, utilizing a precisely designed arm to accurately shoot ping pong balls into the opponent's side of the court.

---
    
## 🧩 Introduction to LEGO EV3
**LEGO Mindstorms EV3** is a versatile platform for learning robotics and developing projects. It features a programmable brick capable of controlling various sensors and motors.

- **Key Components**:
  - **EV3 Brick** (Main Control Unit)
  - **Motors** (DC and Servo)
  - **Sensors** (Ultrasonic, Color, Touch, etc.)
  - **Expandable and Open-Source Programmable**

---
    
## 🛠️ Technology Stack & Components
    
### 🖥️ Hardware
- **LEGO EV3 Modules**
- **Ultrasonic Sensor**
- **Arm Structure Designed to Fit Court Dimensions**
- **Two Driving Wheels**
    
### 💻 Software
- **Pybricks MicroPython**
- **EV3 Brick Firmware**
- **LEGO EV3 IDE or VSCode**

---
    
## 🚀 Key Features
1. **Ball Shooting**
   - Utilizes an arm tailored to court dimensions to launch ping pong balls in designated directions.
2. **Position Adjustment**
   - Uses an ultrasonic sensor to measure distance from walls and stops at optimal positions.
3. **Autonomous Operation**
   - Fully autonomous actions initiated by a start button, adhering to competition regulations.
    
---
    
## 🔧 How It Works
    
### 🎯 Shooting Algorithm
- The robot moves forward while using its arm to shoot a ping pong ball.
- After shooting, it reverses and switches to standby mode.
- Repositions itself for the next shot.

### 📡 Utilizing the Ultrasonic Sensor
- While reversing, the robot continuously measures the distance to the wall using the ultrasonic sensor.
- Designed to maintain an optimal distance of **5cm or more**.

### 🔄 Repetitive Actions
- Repeats shooting and standby actions throughout the match duration.

### 📝 Detailed Algorithm Flow
1. **Initialization**: Initialize motors and sensors, then enter ready state.
2. **Match Start**:
   - **Move Forward**: Move at a speed compliant with competition rules.
   - **Shoot Ball**: Activate the arm motor to launch the ball.
   - **Move Backward**: Reverse while checking distance with the ultrasonic sensor.
   - **Standby**: Prepare for the next shot upon meeting specified conditions.
3. **Match End**: Halt all actions after the set time elapses.
    
---
    
## 📜 Competition Rules Summary
- **Court Size**: 2.4m x 1.2m, enclosed by walls 10cm high.
- **Ball**: Standard ping pong ball with a diameter of 40mm.
- **Robot Specifications**: Maximum dimensions of 200mm x 200mm x 200mm.
- **Regulations**: Robot operates autonomously with no human intervention during the match.
    
---
    
## 🔍 Future Improvements
    
### 🛠️ Hardware Enhancements
- **Motor Upgrade**: Research and develop new motors and components to increase shooting power.

### 💡 Software Enhancements
- **Advanced Vision Processing with OpenMV**:
  - **Ping Pong Ball Detection**: Identify ping pong balls by analyzing color and position.
  - **Approach**: Navigate based on the ball's location.
  - **Ball Grabbing**: Implement precise arm movements to catch the ball.
  - **Shooting**: Launch the ball into the opponent's area from optimal positions.
    
---
    
## 🎥 Match Video
Watch the robot's actions during a match in the MP4 video linked below:

[🎬 View Match Video](https://github.com/your-username/your-repository-name/raw/main/robot-tennis-match.mp4)
    
---
    
## 🛠️ How to Use
    
1. **Upload Code**:
   - Upload the Pybricks MicroPython code to the EV3 Brick.
2. **Prepare for Match**:
   - Position the robot within the green start area (200mm x 200mm) according to competition rules.
3. **Start the Match**:
   - Press the start button to initiate autonomous operation and begin shooting.
4. **Robot Operation**:
   - The robot will execute shots, adhering to competition regulations by shooting balls into the opponent's area.
    
---
    
## 📚 References
- **Competition Rules**: [File: 09_Robot Tennis EV3 Programming.pdf](#)
- **Pybricks Official Documentation**: [Pybricks Documentation](https://pybricks.com/)
- **LEGO Mindstorms EV3 Official Site**: [LEGO EV3](https://www.lego.com/mindstorms)
    
---
    
### ⚠️ Important Notes
- An MP4 file containing the robot's movements during the game has been uploaded to GitHub. 
    
---
