# Home_Security_System-ESP32cam-

Smart Home Security System using ESP32-CAM

Project Description :
This project is an IoT-based smart home security system developed using ESP32-CAM. It monitors the environment in real time and sends instant alerts to the user through Telegram when motion, fire, or smoke is detected.

The system also captures and sends images during intrusion events, enabling remote surveillance from anywhere.

Features
* Motion detection with image capture
* Fire detection alert
* Smoke/Gas detection alert
* Telegram bot notification system
* Remote monitoring using mobile
* Flash support for night images
* Cooldown mechanism to avoid repeated alerts
  
Technologies Used :
* ESP32-CAM
* Embedded C (Arduino IDE)
* IoT (WiFi Communication)
* Telegram Bot API
* Sensors (PIR, Fire, Smoke, Door Sensor)

Working :
Sensors continuously monitor the surroundings
If motion/fire/smoke is detected:
ESP32-CAM captures image
Alert message is sent to Telegram
User receives notification instantly
Cooldown logic prevents repeated alerts

Hardware Components :
ESP32-CAM
PIR Motion Sensor
Fire Sensor
Smoke/Gas Sensor
Reed Switch (Door Sensor)
Jumper Wires
Power Supply

Challenges Faced :
Continuous alert spamming
False sensor triggering
Low image clarity in dark conditions

Solutions Implemented :
Added cooldown logic to control alerts
Used proper condition checks for sensors
Improved image capture using flash and resolution tuning

Future Improvements :
AI-based human detection
Mobile app integration
Cloud storage for images
Buzzer alarm system
