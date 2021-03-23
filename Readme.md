# Recaptcha Solver
University project for Humoan-Computer Communication, intended to solve reCaptcha

## Table of content
* [General info and usage](#General-info-and-usage)
* [Autorship](#Autorship)
* [Technologies](#Technologies)
* [Setup](#Setup)
* [App's Future](#App's-future)

## General info and usage
This app runs entirely in Jupyter Notebook environment. It learns to recognize if image contain crosswalk or not. Other kind of images appearing on captcha were not implemented. 
To run this app one must start all containers in RecaptchaSolver.ipynb file and before doing it uncomment the last line in container starting with '#trenowanie', for the networt to be trained. After first time only using the last one is required (if running in the new session one should run again all (for function to be defined)). 
In the last container (in main() function) one should specify the file which should be checked in array 'nazwy', the files shuold be specified with extension and be placed inside 'input' folder.

## Autorship
This project was made with my university friend, who do the image processing while my part was prepareing the neural network and putting it together.

## Technologies
- JupyterNotebook
- Python 3 
- Tensorflow Keras
- Sklern, Skimage, Shutil, Numpy and Pandas Libraries

## Setup
This app require's no installation(beside libraries), but requires Jupyter Notebook, in which it is run. 
The main file, which is the actual program is RecaptchaSolver.ipynb

## App's Future
As this approach prove to be unsuccesfull, project most likely wouldn't be further developed.