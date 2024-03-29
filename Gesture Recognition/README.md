# Project Name
> Gesture Recognition


## Table of Contents
* [General Info](#general-information)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## General Information
- Develop a feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

1. Thumbs up:  Increase the volume
2. Thumbs down: Decrease the volume
3. Left swipe: 'Jump' backwards 10 seconds
4. Right swipe: 'Jump' forward 10 seconds  
5. Stop: Pause the movie

## Dataset
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 
Each row of the CSV file represents one video and contains three main pieces of information - the name of the subfolder containing the 30 images of the video, the name of the gesture and the numeric label (between 0-4) of the video.

## Technologies Used
- Convolution Neural Network
- Recurrent Neural Network

## Conclusions
- Out of multiple CNN and RNN models 1 final model is decided.
- Final model was built with Multiple Convolution 3D layer and GRU layers.
- Model gave accuracy of 85%

## Contact
Created by [@sirohijai22] - feel free to contact me!
8384044903
