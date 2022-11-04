# license-plate-generator
Python notebook file used to generate augmented license plate images for training a convolutional neural network 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
This notebook aims to generate a large suite of license plate images, each with random letter and number configurations, and distorted to 
simulate how a moving vehicle would perceive them. It is our goal that these images would make up a set of data we may use to train a convolutional
neural network, such that it will perform well in guessing the license plates of other vehicles as it moves by them in simulation.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- OpenCV
- Tensorflow
- Numpy
- Keras


## Features
List the ready features here:
- Generates a large suite of license plate images, each uniquely distorted and/or filtered based on user input
- Flexibility in choices made by user for image distortion and filtering methods


## Project Status
Project is: _complete_ 


## Room for Improvement
- image generation parameters can always be tuned to find the most optimal result for training


## Acknowledgements
Give credit here.
- This project was inspired by the Engineering Physics department at the University of British Columbia, for a class project in machine learning


## Contact
Created by [@carsonsidhu](www.linkedin.com/in/carson-sidhu-4b8464185) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
