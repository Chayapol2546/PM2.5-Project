# PM2.5-Project
At present, our world has a climate that changes frequently and warped very easily. In 
addition, these weather conditions also have a significant impact on our daily lives, such as 
transportation, activities, and health matters. The problem that is currently very current is the 
PM 2.5 air pollution by the project this is provided to help you easily know the amount of 
dust around us. By submitting values including Date/Month/Year, Time, Air Quality, 
Location, and GPS. When the sensor is measured, all this information is sent to the line or on 
the location website. Data can be viewed through the Line app or through a website, where 
data transmission relies on Wi-Fi as an intermediary to transfer data, which is real-time data 
to a preset program. In addition, the device is small and portable, perfect for carrying around 
to know what the values are, allowing you to protect yourself or avoid going to that area.

## Equipment ##
* Microcontroller NodeMCU ESP32
* 20x4 LCD I2C
* Dust censor PMS7003
* Jump wire (male to female)
* Jump wire(male to male)
* Breadboard 400 point
 
 ![](https://imgur.com/owaFJkT.jpg)
 ![](https://imgur.com/XJ2sUn3.jpg)
 
 ## How It Work ##
When connecting a MicroUSB cable to the computer's power supply or serial port that supplies the power supply to the board, the microusb cable is connected to the computer's power supply or serial port. 
NodeMCU ESP32 will be able to operate with a red light on the board (indicating that the circuit is working), and
The sensor starts checking dust values at all times. Use laser light to detect dust particles, communicate with
Serial/UART microcontroller is compatible with all microcontrollers. Compatible with Arduino
NodeMCU will process and send the data to the cloud server.
Cloud Servers like Google Drive send data to Line Developer to:
Put data to line system notifications 

 ## Result ##
 The work of the PM 2.5 dust monitoring system device by IoT network applications 
can be used in real time and alert on the Line BOT system, which can be achieved by the 
function of the PMS7003 Sensor And the results from the experimental table It can be seen 
that the operation of the sensor is reliable. And the function of the device board NodeMCU 
ESP32, PMS7003, LCD 20x4 I2C, Arduino program is also working efficiently from the 
work of PMS7003 that can transmit PM dust quantity data. To alert the system, Line aims to 
develop a PM 2.5 dust monitoring system by using the IoT network and alerting the amount 
of dust to users.
