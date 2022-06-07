# Virtual-Mouse
Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by MediaPipe running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.
# Getting - started
Pre-requisites
Python: (3.6 - 3.8.5)
Anaconda Distribution

Procedure

Step 1:

conda create --name gest python=3.8.5
Step 2:

conda activate gest
Step 3:

pip install -r requirements.txt
Step 4:

conda install PyAudio
conda install pywin32
Step 5:

cd to the GitHub Repo till src folder
Command may look like: cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src

Step 6:

to run only Gesture Recognition :

Uncomment last 2 lines of Code in the file Gesture_Controller.py

python Gesture_Controller.py
