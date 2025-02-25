Project Report: Spy Cam Detection project

Spy Cam Detection Project Overview
1. Introduction
   The Spy Cam Detection project aims to detect hidden surveillance cameras using computer vision and machine learning techniques. The primary goal is to identify unauthorized surveillance 
   devices in homes, offices, or public spaces, enhancing privacy and security.

2. How It Works
    The project captures a live video stream from the user’s device.
   It uses TensorFlow.js and the COCO-SSD object detection model to analyze video frames.
   The system scans for objects resembling cell phones or mobile cameras.
   If a potential spy cam is detected, an alert is triggered.
3. Technical Components
Frontend (User Interface)

    Built with HTML, CSS, and JavaScript.
     Includes a live camera feed and detection overlay.
    Users interact via a web interface.
    Object Detection

    Uses COCO-SSD (a machine learning model for detecting common objects).
    The model identifies objects in real-time and highlights them on the screen.
    Monitoring System

     The camera continuously scans for potential spy cameras.
    If a spy cam is detected, the system alerts the user and stops monitoring.
4. Implementation Details
   JavaScript (script.js)

   Handles camera access using navigator.mediaDevices.getUserMedia.
   Loads the COCO-SSD model and detects objects in real-time.
   Uses an overlay canvas to highlight detected objects.
  CSS (style.css)

   Defines the layout and styling of the web interface.
   Includes styles for buttons, video elements, and alerts.
  HTML Pages
  index.html (not uploaded) – Likely the main page.
  blog.html – Provides information on spy cam threats.
  about.html – Explains the project's mission.


6. Results & Future Enhancements
   The project successfully detects objects resembling spy cameras.
   Future improvements could include:
   Better object recognition for various spy cam types.
   Mobile app development for easier use.
   Integration with home security systems.



8. References -

- TensorFlow.js Documentation: https://www.tensorflow.org/js
- COCO-SSD Model: https://github.com/tensorflow/tfjs-models/tree/main/coco-ssd

![image](https://github.com/tanishq396/Spy_Cam_Detection/assets/65888542/25b429eb-6a4b-4286-81f1-3d1895eb03e8)

![image](https://github.com/tanishq396/Spy_Cam_Detection/assets/65888542/3e573e72-e9d3-46a5-a7de-0ed522885484)

This concludes the report on the Spy Cam Detection project. The system's successful implementation and potential for future enhancements make it a valuable tool in addressing privacy and security concerns related to hidden spy cameras.


