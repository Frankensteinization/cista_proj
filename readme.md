Eyes detection project

In this file, we have:
dlib-19.22.1
command.txt
shape_predictor_68_face_landmarks.dat
test.mp4
Wink.py
readme.txt

Steps:
1. open terminal and open the project directory, like C:\Users\Administrator\Desktop\project>
2. type the command in command.txt. If you want to use a specific video, change the last word that ended by .mp4, like
"python Wink.py --shape-predictor shape_predictor_68_face_landmarks.dat --video 4.mp4"

Environment:
For the dlib, the following steps are:
1. Use the terminal to open dlib-19.22.1 file, like
C:\Users\Administrator\Desktop\project\dlib-19.22.1>
2. Use the command "python setup.py install"

For the rest of lib, we can use cmd to type:
pip install scipy
pip install imutils
pip install argparse
pip install time
pip install opencv-python
