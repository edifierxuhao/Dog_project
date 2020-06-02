# Dog_Breed_Classifier_Project
Udacity dog breed classifier project

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Limitations](#limitations)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Besides the Anaconda distribution of Python, in order to run the machine learning web app, I used the following libraries:
- **Keras**, key library used in python to run CNNs, can be installed using `pip install Keras`
- use `! KERAS_BACKEND=tensorflow python -c "from keras import backend"` to switch keras backend to TensorFlow
- numpy, cv2 and PIL

## Project Motivation<a name="motivation"></a>

Identifying dog breed from photos is one of the most popular Udacity projects across machine learning and artificial intelligence field. The goal is to classify images of dogs according to their breed.
After cleaning, this dataset has 26216 rows ,40 columns, and 36 columns are features of the text.

Specifically, I will take these steps:
- Write a human detection algorithm
- Write a dog detection algorithm
- Create a CNN to Classify Dog Breeds from scratch
- Create a CNN to Classify Dog Breeds using Transfer learning
- Choose a better classifier and make some predictions

## File Descriptions <a name="files"></a>

There is one notebooks(`dog_app.ipynb` ) available here to showcase work related to the project.  This notebooks walk through all processes to finish the project.
The `image` folder has several images used in the notebook.

## Limitations <a name="limitations"></a>

This project has following limitations:
- The accuracy is about 70%, and is not a high score
- It is not very stable, if I run the algorithm twice, it could give two different breed prediction for the same image.
more information please see the [article](https://medium.com/@edifierxuhao123/a-dog-identification-algorithm-using-cnns-and-transfer-learning-91294822744c) I published in medium
## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity the dataset.  
Otherwise, this software is follow a MIT Licenec.

contact email: edifierxuhao123@gmail.com
