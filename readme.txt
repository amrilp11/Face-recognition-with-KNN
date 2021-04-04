Real Time Face Detection and Recognition readme

This program uses webcam of the system you are using. HarrCascade, numpy array and K-Nearest Neighbor algorith are used for detection and recognition.

Following version of packages are used: -
OpenCV - 4.2.0
Python - version 3.8
Other required dependencies : -numpy, csv

face_data_collect.py

This file creates an entry for new user registration. When running this python file, it will first ask for user's name and then it will take the images of user. Press Q to exit the loop.

face_recognition.py 

This file is for face recognition. When you run this file, the program will start classifying people present in the frame. Accuracy will be generated in the background and data will be saved in acc.csv file. The video will also be saved in output.avi file.
