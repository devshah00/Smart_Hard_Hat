# "Noggin" Smart Hard Hat
## Senior Design Project for Purdue University ECE47700 (Digital Systems Design)

**Final Repository:**\
https://github.com/aprasan2000/ECE477/tree/Noggin-final

**Completed:**\
May 2022

**Purpose:**\
The purpose of this project is to design and develop a smart hard hat to protect construction workers. It does this using several sensors that are able to work together to monitor a construction worker's health as well as the working conditions in the surrounding environment. The hard hat is equipped with a heart rate sensor, a carbon monoxide sensor, and an accelerometer. The heart rate sensor is an attachment that must be clipped to the worker's earlobe and can accurately determine if the worker has a high/low heart rate. The carbon monoxide sensor measures the amount of carbon monoxide in the surrounding atmosphere, noticing if dangerously high levels of CO are currently present. An accelerometer is used to determine if an object has fallen and hit the worker or if the worker has fallen. If any of theses scenarios were to happen, an alert would be sent to the supervisor's receiver using a LoRa.


**My Work:**
- Configuring the heart rate monitor to alert the supervisor if it measures a heart rate either below 40 BPM or above 180 BPM
  - Results comparable to Apple Watch's heart rate monitor function
- Configuring carbon monoxide sensor to alert the supervisor if it measures carbon monoxide over 50 ppm
- Configuring accelerometer to send an alert if it detects a free fall
- Designed LoRa communcicator to send alerts using the I2C pins
