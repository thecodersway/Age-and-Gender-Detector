# Age-and-Gender-Detector
Predictor using OpenCV. 

Let’s divide the task into 2 parts: 

Age prediction – The prediction will be in the form of categories where categories are a few age intervals like  0-6,18-25, etc.
Gender prediction – The prediction is a classifier based where categories are Male and Female.
The approach followed for each task is as follows 
The main problems in this project are the quality of the camera, brightness in the room, the background of the person, the boy cut in the case of girls/the long hair of boys.

The solution to this problem is quite simple, instead of predicting an exact image, we will work on the face of the person only. The flowchart below shows the flow of code.

![image](https://github.com/thecodersway/Age-and-Gender-Detector/assets/125991240/d2bc0c28-b4cd-4c63-bf84-3614d52798d3)
