# Arduino Sensor Hub

This folder contains the Arduino code used in the Brainy autonomous rover system.

## Purpose
The Arduino Mega acts as the rover’s sensor hub, responsible for:
- Reading ultrasonic sensors  
- Reading IR obstacle sensors  
- Monitoring tilt and shock sensors  
- Reading environmental sensors (DHT11, moisture, rain, light)  
- Sending processed sensor data to the Jetson Nano  
- Triggering safety events (stop, disarm, hold) via Pixhawk  

## Files
- **brainy_sensor_hub.ino** – main Arduino program  
- **/libraries** – custom libraries for sensors or MAVLink if needed  
