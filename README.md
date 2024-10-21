# Vehicle-Accident-Detection
 Developing a sophisticated system to quickly detect accidents and track vehicles in real-time  for enhanced safety and security.


```markdown
# Vehicle Accident Detection System

## Overview

The Vehicle Accident Detection System is an Arduino-based project that detects accidents and alerts the user through various sensors. The system utilizes an LCD to display status messages, an alcohol sensor to ensure the driver is sober, an infrared sensor for seat belt detection, and a vibration sensor to detect any sudden movements indicative of an accident. Upon detecting an accident, the system sends an SMS alert with the vehicle's GPS location.

## Features

- **Seat Belt Detection**: Checks if the seat belt is fastened using an infrared sensor.
- **Alcohol Detection**: Ensures the driver is sober by checking the alcohol sensor.
- **Accident Detection**: Uses a vibration sensor to detect sudden movements or impacts.
- **SMS Alerts**: Sends SMS notifications with the GPS location to a predefined mobile number in case of an accident.
- **LCD Display**: Provides real-time feedback on the system status, including messages for seat belt status, alcohol detection, and accident detection.

## Components Required

- Arduino Board (e.g., Arduino Uno)
- LCD Display (16x2)
- GPS Module
- Alcohol Sensor
- Infrared Sensor
- Vibration Sensor
- Buzzer
- Relay Module
- Jumper wires and breadboard

## Wiring Diagram

![Wiring Diagram](path/to/your/wiring_diagram.png)  
*(Replace with the actual path to your wiring diagram image)*

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Vehicle-Accident-Detection-System.git
   cd Vehicle-Accident-Detection-System
   ```

2. **Open the Project**: Use the Arduino IDE to open the `accident_detection_system.ino` file.

3. **Connect Hardware**: Connect the components as per the wiring diagram.

4. **Upload Code**: Select the appropriate board and port in the Arduino IDE and upload the code.

## Usage

1. Power on the system.
2. Ensure the seat belt is fastened for the system to operate.
3. The system will check for alcohol presence and will only allow the vehicle to start if no alcohol is detected.
4. In the event of an accident (detected by the vibration sensor), the system will send an SMS alert to the predefined mobile number with the GPS location.

## Notes

- Replace the mobile number in the code with your own for testing SMS functionality.
- Ensure proper calibration of sensors for accurate readings.
- Test the system in a controlled environment before deploying it in a real vehicle.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Arduino community for the incredible support and resources.
- TinyGPS library for GPS functionalities.
- LiquidCrystal library for interfacing with the LCD display.
```
