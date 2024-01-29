# Hand_gestured_robot
# Hand Gesture Controlled Robot with L298N Motor Driver and ESP32 Integration

This project involves building a hand gesture controlled robot using Python, OpenCV, MediaPipe, L298N motor driver, and ESP32. The robot's movements are controlled based on hand gestures recognized by the camera.

## Prerequisites

Before starting the project, ensure you have the following components and software installed:

### Hardware Components
- L298N Motor Driver
- ESP32 microcontroller
- USB cable for connecting ESP32 to your computer
- Robot chassis with motors and wheels
- Camera (built-in or external) for hand gesture recognition

### Software Requirements
- Python (with OpenCV, Mediapipe, and NumPy libraries)
- Arduino IDE

## Installation and Setup

### Installing Python Libraries
1. Install Python on your system if not already installed.
2. Install required Python libraries using pip:

### Configuring Arduino IDE for ESP32
1. Open Arduino IDE.
2. Go to **File > Preferences**.
3. In the "Additional Board Manager URLs" field, enter the following URL: https://dl.espressif.com/dl/package_esp32_index.json
4. Click **OK**.
5. Navigate to **Tools > Board > Boards Manager**.
6. Search for "ESP32" and install "ESP32 by Espressif Systems".
7. Once installation is complete, select your ESP32 board from the **Tools > Board** menu.
8. Connect your ESP32 board to your computer via USB cable.
9. Select the appropriate port from the **Tools > Port** menu.

## How to Use

1. Clone or download the provided Python script.
2. Connect your camera to the computer.
3. Connect the motors to the L298N motor driver and the ESP32 microcontroller as per the provided schematic.
4. Ensure that the ESP32 is programmed to receive commands from the Python script over UDP.
5. Open the Python script in your preferred editor or IDE.
6. Modify the script to match your ESP32's IP address and port if necessary.
7. Run the Python script.
8. Make the necessary hand gestures in front of the camera to control the robot:
- Move your hand left or right to steer the robot.
- Place your hand within the defined boxes to make the robot move forward or backward.
9. Monitor the robot's movement and the detected hand gestures from the Python script's output.
10. To stop the program, press 'q' in the Python script window.

## Additional Resources

For detailed tutorials on using the L298N motor driver and integrating ESP32 with Arduino, refer to the following resources:
- [How to use L298N motor driver](https://www.youtube.com/watch?v=dyjo_ggEtVU&ab_channel=DroneBotWorkshop)
- [How to add ESP32 to Arduino](https://www.youtube.com/watch?v=mBaS3YnqDaU&ab_channel=RuiSantos)

