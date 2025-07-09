# Anti_Theft_vehicle_protection
Anti_Theft_Vehicle_Protection

## Anti-Theft Car Security System

This project is a low-cost, Raspberry Pi–based anti-theft security system designed for vehicles. It uses a combination of GPS, GSM, camera, and buzzer modules to monitor the vehicle and alert the owner in case of suspicious activity. When triggered, the system sends the vehicle’s live location through SMS using the GSM module and also uploads it to Firebase for real-time tracking. A camera module takes the image of the scene, which are made available through a Flutter-based mobile app. Additionally, a buzzer is used to sound an immediate local alarm during a breach.

To make the system more intelligent(which we didnt implement), OpenCV is integrated for face detection. This ensures that the camera only captures images when a human face is detected, helping to avoid false alarms caused by random motion or objects. The face detection feature also allows the system to detect intruders , which can be stored locally or uploaded to the cloud for review.
