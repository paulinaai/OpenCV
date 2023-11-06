# OpenCV
Open CV Project for Waking Students Up!

This project uses computer vision as well as Eye Aspect Ratio to determine in live video feed whether a student is asleep or not. 
The program will awaken the student with an alarm if their eyes are detected to be closed for too long. 
This program has possible uses towards driving-drowsiness detection. 


Instructions: Before anything, download the files titled "" and "". 

These are the pre-trained facial landmark predictor and the alarm sound files, respectively. 
They should all end up in the same folder as "cv_project.py" for my program to 
work normally.   

Then, in your command line, once you are in the folder that contains "cv_project.py" as well as the facial landmark
predictor and alarm sound file run this line: 
python cv_project.py \--shape-predictor shape_predictor_68_face_landmarks.dat

The program is supposed to set the alarm off if your eyes have been closed for 10-20 minutes, but becase that is
far too tedious to test, it goes off in only about 30 seconds of having your eyes closed. 




