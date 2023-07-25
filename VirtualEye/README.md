# Drowning-Detector

Introducing our drowning detection system, designed to detect and alert when someone is in danger of drowning.
Our system uses computer vision algorithms to analyze video feeds from multiple cameras around a pool or other bodies of water.

The system works by using a deep learning-based object detection model to identify a person in the water. The model is trained on thousands of images and videos of people in water environments, allowing it to accurately recognize a human body in a variety of positions and lighting conditions. Once a person is detected, the system uses motion analysis algorithms to track their movements and monitor their safety.

Overall, the drowning detection system provides an innovative and effective solution for ensuring the safety of people in and around swimming pools. By leveraging advanced computer vision and machine learning technologies, the system can quickly and accurately identify potential drowning incidents and alert caregivers, ultimately helping to save lives.

To install the necessary packages, run
`pip install -r requirements.txt`

## To run this program you can follow these steps:

1. Clone the project .
2. Download the yolov3.weights file from this link:
   https://github.com/patrick013/Object-Detection---Yolov3/blob/master/model/yolov3.weights
3. Then put this file inside the folder
4. open your command prompt
5. go to this project directory and type the commmand: python app.py
6. this will open the website and now you can upload the required videos to detect drowning
