# Infant-Security-System

Welcome to the Infant Security System Project!

Program utilizes the Arduino Nano along with GPS/GSM Modules to track your child's location and send it via SMS when needed.

Project consists of multiple parts:

- Reading SMS:  The GSM Module waits for an SMS message from the user. Once the appropriate text has been sent, the program is redirected to the get GPS functions.
- Get GPS Location: The GPS Module is used to determine the exact, latitude, longitude and altitude coordinates of the child. The coordinates are then used to string a Google Maps link of the exact location
- Send SMS: The Google Maps link generated in the Get Location function is then sent using GSM module to the parent's prestored phone number
