Overview: 
This project is an Arduino-based automated irrigation system that monitors soil moisture levels and controls a motor pump via a relay module to ensure efficient watering. The system provides real-time status updates through an LCD display and logs sensor readings via the serial monitor.

Features: 
Soil Moisture Monitoring – Reads real-time moisture levels from the sensor.
Automated Watering – Controls a relay module to turn the motor pump ON/OFF based on soil conditions.
LCD Display Integration – Shows system status and moisture readings.
Error Detection – Alerts if the sensor is disconnected or malfunctioning.
Serial Monitoring – Outputs sensor data and system logs for debugging.

Components Used: 
Arduino UNO Board,
Soil Moisture Sensor,
Relay Module,
Motor Pump,
I2C LCD Display,

How It Works: 
The moisture sensor reads the soil condition and sends data to the Arduino.
If moisture is low, the relay module activates the motor pump to start watering.
If moisture is moderate or high, the pump remains OFF.
The LCD display shows the current soil condition and watering status.
The system logs all readings via the Serial Monitor for debugging.

Installation & Usage: 
Connect all components as per the circuit diagram.
Upload the provided Arduino sketch to your Arduino board.
Open the Serial Monitor (9600 baud rate) to view sensor readings.
Monitor soil status on the LCD and let the system automate watering.

License: 
This project is open-source. Feel free to modify and improve!
