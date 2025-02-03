🌱 Smart Plant Watering System using ESP8266 & Blynk IoT

 Overview:-

This Smart Plant Watering System automates plant irrigation using an ESP8266 microcontroller and Blynk IoT. It monitors soil moisture levels and activates a water pump when needed, ensuring efficient plant care. The system also provides real-time monitoring and remote control via the Blynk app.

🔧 Features:-

  ->Automated Watering – Uses soil moisture data to activate a water pump.
  
  ->Blynk IoT Integration – Monitor and control watering remotely via a smartphone app.
  
  ->Real-time Sensor Data – View soil moisture, temperature, and humidity in real time.
  
  ->Manual Control – Option to manually turn the water pump ON/OFF from the app.
  
  ->Power-efficient – Only activates when moisture is low, conserving water and energy.

🛠️ Components Used
1.	ESP8266 (Node MCU)
2.	Soil Moisture Sensor.
3.	Relay Module.
4.	Bread Board.
5.	Jumper wires.
6.	12v DC Motor Pump.
7.	LCD display
8.	I2C Protocol  Module

🔌 Circuit Diagram

![Image](https://github.com/user-attachments/assets/904de961-d246-48d6-9430-55428553011d)


📌 Installation & Setup

->Install Blynk App and create a new project.

->Add Widgets: Gauge for moisture, Button for manual control.

->Get Auth Token from Blynk and update it in the code.

->Connect ESP8266 to Wi-Fi (update credentials in code).

->Upload Code to ESP8266 using Arduino IDE.

->Power the Circuit and monitor the plant remotely!

📱 Blynk Dashboard Preview

![Image](https://github.com/user-attachments/assets/5f53c4b9-e460-4fb0-b48b-1416631c89e0)
![Image](https://github.com/user-attachments/assets/93fa3953-09c7-48ce-b8c4-69379e1c5348)

🎯 Future Improvements

🔹 Add water level detection to prevent pump damage.

🔹 Integrate weather API to optimize watering based on forecasts.

🔹 Use solar power for a fully autonomous system.

🤝 Contributing

Feel free to fork this repo, make improvements, and submit a pull request! 🚀
