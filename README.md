# Face-Recognition-Attendance-System

Libraries used for this project are os, cv2, numpy, face_recognition and datetime.
1. OS -  provides a portable way of using operating system dependent functionality. Helps in when we want to read or open a file.
2. CV2 - known as Open CV library which is very usefull in video capturing or video analysis or image analysis.
3. NUMPY - is a great python library for multi dimesnsional array and matrix processing with the help of large collection of mathematical functions.
4. FACE_RECOGNITION -  is a python library that provides an easy-to-use interface for face detection and recognition. Modern facial recognition created with deep learning is used in the library by dlib.
5. DATETIME -  supplies classes to work with date and time. These classes provide a number of functions to deal with dates, times, and time intervals.

# Basic Flow

We grab the list of images that are stored in the "Images_Attendance" folder and save it. We then find the encodings for the list of images we grabbed from the folder. These encodings are used to match with the image that our video camera captures in order to tell identity of the person. After getting a successfull match the program will write the name with it the time and date it recognised the person in an output file "attendance.csv".

INPUT

We have these three images stored in our "Images_Attendance" folder which will act as a reference for identifying them.
![image](https://github.com/AshleyTirkey/Face-Recognition-Attendance-System/assets/87265518/40964446-11f0-40e9-8fef-eeac61f31c97)

EXECUTION:

After executing the program it will find the encdoings for the refernce image and initiate a web cam to capture the video



Upon capturing my face it matches with the encodings that are stored and upon no match it is not able to recognize the person.
![Screenshot 2023-08-01 171322](https://github.com/AshleyTirkey/Face-Recognition-Attendance-System/assets/87265518/48de5fa6-f4b1-43c6-98cd-9a80f476e01e)
![Screenshot 2023-08-01 171357](https://github.com/AshleyTirkey/Face-Recognition-Attendance-System/assets/87265518/94324a77-dd56-425c-a8af-94529535c042)
![Screenshot 2023-08-01 171413](https://github.com/AshleyTirkey/Face-Recognition-Attendance-System/assets/87265518/0545f378-ecb6-4d57-8981-3b78f9f20ac8)


When showed an image of any of the three reference images it is able to match the encoding with the image its capturing and will present the name of the person as well as store the name with it its time and date of when it recognised the person.
![image](https://github.com/AshleyTirkey/Face-Recognition-Attendance-System/assets/87265518/0eaafe1c-4995-4ad6-80bb-a6515233a5d2)


