[Home](/README.md) | [Gestures](/gestures.md) | [Reference](/reference.md) | [Edit Guide](/editguide.md) | <button class="nav" ><a href="https://github.com/whatifif/handgesture/">View on Github</a></button>  |  <button class="nav" ><a href="https://whatifif.github.io/handgesture/">View on Web</a></button>

project homepage: [https://github.com/whatifif/handgesture](https://github.com/whatifif/handgesture)  
project code page: [https://github.com/whatifif/handgesturecode](https://github.com/whatifif/handgesturecode)  
project slack: [https://sml109.slack.com](https://sml109.slack.com)  
project team name: Team Echo

# Controlling a Computer by Hand Gesture


## Brief Introduction of the project of Team Echo

Almost people use a desktop or laptop these days. One of serious problem is that we are stuck to the keyboard and mouse, which will cause a serious health problem on a long run. Moreover in VR/AR age, we cannot use keyboard/mouse. Our purpose is to replace a keyboard and mouse with hand gestures. We have devised a virtual keyboard and virtual mouse with subtle hand gestures and made ML recognise our gestures so that we can control our computer remotely. Amazon echo has ear now. It will have eye in future. We need to make a standard gestures for people to adopt easily like a standard keyboard and mouse. ML will address this for us, human. We used Deep Learning as ML in this project.

# handgesturecode
code for handgesture project

## Dependencies
- MxNet 0.11.0
- Numpy 1.13.1
- Pandas 0.20.3
- Opencv 3.2.0
- Python2.7
- Jupyter Notebook

Best to install Anaconda2 :) 

## Run the Code
```
jupyter notebook
```
and run the main.ipynb

## How to use the main program

- Press g to enter GUI mode to capture a hand image
- Press d to enter demo mode
- Press d and Press c to enter calculator mode
- Press m to add mouse mode
- Press esc to quit program


## Model is trained by 200x200 pixel images and 64x64 pixel images

200x200 pixel data caused the out of memory problem on NVdia GTX 960 ( 2GB Graphic memory).  
So 64x64 version of data and program is prepared.










