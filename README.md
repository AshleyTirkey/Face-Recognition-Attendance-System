# Face-Recognition-Attendance-System

Libraries used for this project are os, cv2, numpy, face_recognition and datetime.
1. OS -  provides a portable way of using operating system dependent functionality. Helps in when we want to read or open a file.
2. CV2 - known as Open CV library which is very usefull in video capturing or video analysis or image analysis.
3. NUMPY - is a great python library for multi dimesnsional array and matrix processing with the help of large collection of mathematical functions.
4. FACE_RECOGNITION -  is a python library that provides an easy-to-use interface for face detection and recognition. Modern facial recognition created with deep learning is used in the library by dlib.
5. DATETIME -  supplies classes to work with date and time. These classes provide a number of functions to deal with dates, times, and time intervals.

# Basic Flow

We grab the list of images that are stored in the "Images_Attendance" folder and save it. We then find the encodings for the list of images we grabbed from the folder. 

These encodings are used to match with the image that our video camera captures in order to tell identity of the person. After getting a successfull match the program will write the name with it the time and date it recognised the person in an output file "Attendance.csv"
