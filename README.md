# IoT Smart Home Environment Monitoring and Control

## Overview
This project simulates a smart home environment monitoring system using IoT concepts. It reads simulated sensor data for temperature, humidity, and light levels, controls a virtual smart light based on light intensity, logs data to a CSV file, and visualizes the collected data.

## Features
- Simulated sensor readings for temperature, humidity, and light level.
- Actuator control to switch a smart light ON or OFF based on light intensity.
- Data logging to CSV file.
- Data visualization with time-series plots..
- Modular Python code suitable for extension to real sensor integration and cloud communication.

- -------------------------------------------

## How to Run
1. Clone the repository.
2. Run `iot_smart_home.py` using Python 3.
   ```bash
   python iot_smart_home.py
Requirements
Python 3.x
-----------------------------------------------
matplotlib (for plotting)

Install matplotlib if needed:

bash
Copy
Edit
pip install matplotlib
Project Structure
bash
Copy
Edit
.
├── iot_smart_home.py  # Main Python script
└── README.md          # Project documentation
Future Enhancements
Connect to real sensors (e.g., DHT11, light sensors) using Raspberry Pi or ESP32.

Use MQTT or HTTP protocols to send data to cloud services.

Implement real actuator control (e.g., relay, smart bulbs).

Add a web dashboard for real-time monitoring.

Enjoy building your IoT smart home!

python
Copy
Edit

---------------

### How to get this running in **Google Colab**:

1. Save the above Python code into a file named `iot_smart_home.py` inside your Colab environment:

```python
with open('iot_smart_home.py', 'w') as f:
    f.write("""<paste the python code here as a raw string>""")
Run the script using:

python
Copy
Edit
!python3 iot_smart_home.py
