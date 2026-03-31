# Digital Temperature \& Humidity Terminal 

### **Author:** G.M Taqi Shah



**1. Project Description**

This project implements a real-time environmental monitoring system. It interfaces a DHT22 digital sensor with an SSD1306 OLED display (128x64) to visualize temperature and humidity data. The system utilizes the I2C communication protocol for the display and a single-bus digital protocol for the sensor data.



**2. Hardware Components (Simulated)**

Microcontroller: Arduino Uno R3



Sensor: DHT22 (Advanced Temperature \& Humidity Sensor)



Display: SSD1306 OLED (128x64 pixels, I2C Interface)



Connectivity: Jumper wires (Breadboard setup)



**3. Pin Configuration**

The following table defines the hardware wiring used in the simulation logic:



**1. DHT22 Sensor**

| DHT22 Pin | Arduino Pin | Description |

| :--- | :--- | :--- |

| \*\*VCC\*\* | 5V | Power Supply |

| \*\*SDA / Data\*\*| Digital Pin 2 | Data Signal |

| \*\*NC\*\* | Not Connected| Leave Empty |

| \*\*GND\*\* | GND | Ground |



**2. SSD1306 OLED Display (I2C)**

| OLED Pin | Arduino Pin | Description |

| :--- | :--- | :--- |

| \*\*VCC\*\* | 5V / 3.3V | Power Supply |

| \*\*GND\*\* | GND | Ground |

| \*\*SCL\*\* | A5 | Serial Clock |

| \*\*SDA\*\* | A4 | Serial Data |

| \*\*RES\*\* | Digital Pin 4 | Reset Pin (Optional) |



**4. Software Requirements**

To compile this project locally or in Wokwi, the following libraries must be installed:



Adafruit SSD1306 (Display Driver)



Adafruit GFX Library (Graphics Support)



DHT Sensor Library (Sensor Communication)



Adafruit Unified Sensor (Base Library for DHT)



**5. How to Run**

Open the project in Wokwi.



Ensure the diagram.json reflects the pins mentioned in the Pin Configuration section.



Add the required libraries in the "Library Manager" tab.



Click the "Play" button to start the simulation.



Click on the DHT22 sensor during simulation to manually adjust the temperature/humidity sliders and see real-time updates on the OLED.



