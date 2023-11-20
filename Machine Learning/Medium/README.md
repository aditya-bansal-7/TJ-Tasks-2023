# Task 2 
### Difficulty level _**Medium**_.

## Real-time Face and eye detection using OpenCV. 
Use Googe Colab to write code and submit it.
When you write the code you are required to explain what code in each cell is doing in brief.

What you will need:
1. XML file of a trained Haar Cascade classifier. Available on [Github Repo of opencv](https://github.com/opencv/opencv/tree/master/data/haarcascades).
   1. Frontal Face Classifier
   2. Eye classifier
2. A working webcam
   
You are required to perform the following tasks:

1. Install cv2
2. Load the xml files you downloaded from opencv github repo. 
3. Capture video of the user using the webcam. (Since its realtine detection)
   Note: If your web cam feed is lagging, you can limit the number of frames to reduce stress on system.
4. Start detecting every frame of the video. 
5. Input into classifier.
6. Draw rectangle around the detected faces. The rectangle should be labelled with your name and the colour of its edges should be yellow.
7. Show the output. Output should be a rectangle around the face of the user.

### How to submit:
There will be two submissions in this case:
1. Link of the Google Colab Notebook which has your code. 
2. A video of the face detection system. (Use [OBS studio](https://obsproject.com/) to record the screen.)
   
