# Tip_the_Scales

A program that will distinguish between different types of 7-note scales (major, minor, harmonic minor, and melodic minor scales) in an audio file.

# Deployment Instructions

Use this program through PyCharm CE! 

1. Download this repository on your computer.
2. Make sure you have [Python3](https://www.python.org/downloads/) installed on your computer (MAKE SURE IT IS PYTHON 3.7)
3. Open the project folder in a Python IDE. We recommend using [Pycharm CE](https://www.jetbrains.com/pycharm/download/#section=mac) by Jet Brains which can be downloaded for free.
4. Set up your Python3 interpreter and make sure the following modules are installed. Before installing these modules on your IDE, you have to download them on your computer using "pip3 install --" (the dash represents the module names):
    - tensorflow
    - keras
    - librosa
    - image
    - numba==0.48 (when downloading this in the IDE, you will have to specify this version of the module specifically)
    - matplotlib
    - os
    - sounddevice
    - write
    - numpy
5. Open *"common_western_scales/predict-with-recording.py"* and run the code (make sure you read the instructions at the top of the file).

**Disclaimers and Notes:**
- Python IDE Step 4: These are the modules we had to download when making this project. We noticed that the modules we had to download differed between teammates, so you may need to download additional ones.
- Python IDE Step 4: To install the modules in Pyharm CE, go to **Preferences->Project: common_western_scales->Project Interpreter**, and then **click the "+" sign** at the bottom left of the preferences window

# Contributions

This project was made between June 24-26, 2020 for the University of Waterloo Software Engineering Class of 2025 Hackathon.

**Team members:**
- Carol Xu
- Dhruv Rawat
- Rahul Aggarwal
