# Raspberry-Pi-Industrial-IoT


Raspberry Pi Industrial Monitoring, Management, and Data Acquisition System RFID Reader checks the validity of a RFID Card. If the card is valid, RPi sends an alert to the phone through Pushbullet, and then uses DHT11 to capture Temperature and Humidity values continuously, and plots them on ThingSpeak

# Requirements

a) Raspberry Pi 3 Model B+

b) RC522 RFID Reader and Card

c) Adafruit DHT11 sensor

d) LEDs and Buzzers

e) Jumper Wires

f) Pushbullet

g) ThingSpeak

# Raspberry Pi Model 3B+

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/db4c911a-daaf-4e90-a467-8b5e8a755198)



![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/4092dc90-86d5-4d10-9c8c-6fbbcf013d2e)




# Raspbian / Raspberry Pi OS

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/2133a21f-3acb-4cfc-b667-5e9c701c0edd)




# Adafruit DHT11 sensor

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/9f360156-64f9-458d-8880-83b5b8f1b8ba)


# RC522 RFID Reader

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/88f46e4d-0024-477c-83da-bd74fd2d93e6)


# LEDs and Buzzers

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/c675223d-85e2-4a4c-bd76-067857b387c7)



![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/1f916543-c910-49e0-bcab-b4a2a9b16859)



# Pushbullet

https://www.pushbullet.com/


![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/f5f0b815-baee-442d-aa77-cde0cd7eb1a8)


# ThingSpeak

https://thingspeak.com/

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/3cdc35aa-5d05-4e04-bcd0-1ead047da097)


![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/97c8cc43-10d9-4d0a-8129-c7df152ce845)



# Block Diagram

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/29ac6d38-8896-425c-b7c6-5ef279557de6)


# Flowchart

![Flowchart](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/5bfb02e5-94be-4553-b84a-e024b4f4aebb)


# Circuit Diagram

Connect the Vcc pin of DHT11 Sensor to Pin 2 of Raspberry Pi, Gnd pin of DHT11 Sensor to Pin 6 of Raspberry Pi and the Out pin of DHT11 Sensor to GPIO 26 of the Raspberry Pi. Also connect the + terminal of LED to GPIO 21, + terminal of buzzer to GPIO 20 and connect the ground pins of both to Pin 6 of Raspberry Pi.

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/9d6679c1-562d-4579-b995-06faebf587ea)


![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/2518b397-0cb2-4b13-b481-7a5876aaf5c9)


# Setup

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/ec7d1995-5e41-400e-b482-b1c21f7a758c)



# Results

ThingSpeak: https://thingspeak.com/channels/2304287


Program output in shell
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/4e31670e-d249-48dc-8b71-ce28717ef94d)







<br>

LED glowing, indicating invalid RFID
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/49cbc061-4a85-4ecd-b8b9-a4bdb6bc6f21)










<br>

Pushbullet notifications on phone
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/4832ba15-a5de-4a27-bc48-8ef6c5d5b036)









Temperature and Humidity values plotted against time in ThingSpeak
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/9aa8281d-9cae-45d2-8082-d9de79c98579)

![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/c9361975-1df0-4938-9eb2-7b072860aaf9)





Temperature and Humidity gauges in ThingSpeak
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/29584991-2a59-4fcc-9555-6f1d45eff876)


![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/72232024-096f-4f96-9591-c90bb8e89c4e)





Temperature and Humidity numeric displays in ThingSpeak
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/0a7a1fd3-c4da-48d2-a455-7208a86118d7)





Correlation between Temperature and Humidity plotted in ThingSpeak
![image](https://github.com/KarthikT23/Raspberry-Pi-Industrial-IoT/assets/119528503/a22fbe89-0f48-4dd7-9081-9ae0d0d3c580)



# References
[1] An Internet-Based Interactive Embedded Data Acquisition System for Real-Time Applications by Ali Ziya Alkar and Mehmet Atif Karaca, IEEE Transactions on Instrumentation and Measurement, Vol. 58, No. 3, March 2009.

[2] Wireless SCADA for industrial automation using Raspberry Pi by Avinash V. Ghadage, Dr. S. S. Patil, International Journal of Advanced Research in Innovative Ideas in Education (IJARIIT), Vol. 3, Issue 4, April 2017.

[3] Low-Cost Solutions for Maintenance with a Raspberry Pi by M. V. K. Sivakumar, S. V. Krishna, M. V. N. Srinivas, International Journal of Emerging Technology in Computer Science & Electronics (IJETCSE), Vol. 10, Issue 11, November 2019.

[4] Internet of Things (IoT) based Data Acquisition system using Raspberry Pi by A. S. Patil, D. S. Patil, S. S. Patil, International Journal of Engineering Research & Technology (IJERT), Vol. 3, Issue 5, May 2014.

[5] Raspberry pi based data acquisition system using wireless communication by V. N. Patil, A. S. Patil, International Journal of Recent Engineering Science (IJRES), Vol. 3, No. 2, February 2015.

[6] https://iotdesignpro.com/projects/home-security-system-using-raspberry-pi-and-pir-sensor-with-push-notification-alert

[7] https://iotstarters.com/how-to-send-sensor-data-to-thingspeak-using-raspberry-pi/

[8] https://www.raspberrypi-spy.co.uk/2017/09/dht11-temperature-and-humidity-sensor-raspberry-pi/

[9] https://learn.adafruit.com/adafruit-io-basics-digital-output/python-setup

[10] https://github.com/alaub81/rpi_sensor_scripts/tree/main
