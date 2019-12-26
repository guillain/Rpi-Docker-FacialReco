# Rpi - Docker - FacialRecognition
All in 3 CLI if you already have a Raspberry with docker. 

All **congrats for M. Marcelo** who has done the dev, I've just put that in container.

https://www.hackster.io/mjrobot/real-time-face-recognition-an-end-to-end-project-a10826

X11 externalized, means you have the graphical output from your docker ;)

## Pre-requisite
- Raspberry min 3
- docker installed and running with the *pi* user
- camera up and running

## Easy Run
1/ create your dataset with your face: `./run 01_face_dataset.py`

2/ train and create model: `./run 02_face_training.py`

3/ run the recognition: `./run 03_face_recognition.py`

## Toplay with OpenCV
- `./run` ... and jump in the container to play with
 
