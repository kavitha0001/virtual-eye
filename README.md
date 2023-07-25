## virtual-eye
The VirtualEye yolo based AI model provides an in-depth look into this life-saving system, showcasing its features and functionality. Basically the person detection is using yolo and drowning detection is based on the motion of the person. If the detected one or more persons have no vertical or horizontal motion for nearly 10 seconds then the person is detected to be drowning. This model can be deployed in security camera near the pools to detect drowning in real-time.

## flowchart
<p align="center">
<img src="videos/1.png" width="290" height="440">
</p>

## To run this program you can follow these steps:

To install the necessary packages, run
`pip install -r requirements.txt`

1. Clone the project .
2. Download the yolov3.weights file from this link:
   https://github.com/patrick013/Object-Detection---Yolov3/blob/master/model/yolov3.weights
3. Then put this file inside the project folder
4. create a folder called vidoes and put the vidoes that you want to check for drowning
5. open your command prompt
6. go to this project directory and type the commmand: python DrownDetect.py --videofilename.mp4
7. this will open the same video detecting the drowning frame by frame
