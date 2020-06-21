In the fight against coronavirus, social distancing has proven to be the most effective way to reduce the spread of the disease. While millions of people stay home to help shorten the curve, many customers in the construction and pharmaceutical industry still have to go to work every day to make sure our basic needs are met.

To help validate the social isolation protocol in their work, I've developed an AI-enabled AI detection tool that can detect if people maintain a safe distance from one another by analyzing real-time video streaming from the camera.

The program makes sure to: 
1. Detect the humans in the frame with yolov3 convolutional neural network.
2. Calculate the distance between all the instances of humans detected in the frame.
3. Classify the determined distances as 'Alert' or 'Ok' for social distancing.

### Output (Video)
This demo video is performed on the public “OXFORD TOWN CENTRE” dataset

### Requirements:

1. Numpy
2. Time
3. OpenCV
4. OpenCV_Contrib
5. Math

### Installation of Model:

* To deploy algorithm on images, python SDD_Image.py
* To deploy algorithm on videos, python SDD_Video.py
* To deploy algorithm on live streaming webcam, python SDD_Camera.py


Reference: https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/
