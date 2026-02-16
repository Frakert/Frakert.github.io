---
title: "MyRIO Biometric Bodysuit"
excerpt: "BSc Thesis Predictive Maintenance <br/><img src='/images/body_suit.png'>"
collection: portfolio
---

This project involved the development of a wearable biometric bodysuit during an internship at VI Technologies, utilizing the National Instruments myRIO as the central processing unit. The primary objective was to create a mobile system capable of real-time monitoring of both body movement and vital signs, including heart rate and blood oxygen levels.

The system integrated three types of I2C sensors to capture a wide range of data: an oximeter for heart rate and blood pressure, an AHT20 for temperature and humidity, and three ICM20 Inertial Measurement Units (IMUs) for tracking acceleration and orientation. To overcome the hardware limitation of having three IMU sensors with only two unique addresses, the architecture was designed to split the sensors across two separate I2C buses.

On the software side, the project featured a Real-Time application developed in LabVIEW to manage sensor data independently. A public API was established using the LV-MQTT-Broker toolkit, allowing for seamless data access by external applications. This was demonstrated by creating a Python-based MQTT client that streamed orientation data directly into Blender, enabling live 3D character animation based on the wearer's movements.

The hardware development focused on portability and durability. Custom 3D-printed "watch-style" housings were designed for the wrist-mounted IMU sensors to ensure stable placement and protection. To power the myRIO on the go, the system utilized a 3-cell 5200 mAh LiPo battery, providing approximately two and a half hours of runtime. A critical safety feature was the integration of a low-voltage cutoff switch, calibrated to disconnect power at 9V to prevent deep discharge and ensure the longevity of the battery cells.


(VI Tech blog post)[https://www.vi-tech.nl/en/blogs/myrio-based-biometric-bodysuit]
(YouTube video demo)[https://www.youtube.com/watch?v=qjQ_R46VZ4M]