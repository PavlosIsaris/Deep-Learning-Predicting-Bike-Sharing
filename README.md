## Deep Learning Nanodegree Foundation Project From Udacity

## Predicting Bike-Sharing Data

Developed as coursework for Udacity "Deep Learning Fundamentals" Nanodegree. In this project, I built a neural network to predict daily bike rental ridership.

[image1]: ./outputs/TrainingOutputNumbers.png "TrainingOutputNumbers"
[image2]: ./outputs/TrainingValidationLoss.png "TrainingValidationLoss"
[image3]: ./outputs/PredictionsCheck.png "PredictionsCheck"

## Further Explanation

The Neural network was built from "scratch", using only NumPy to assist. The goal of this project is to understand what happens behind the neural network before diving deeper into other tools like TensorFlow.

## Methods and Frameworks utilized

- **NumPy** - a fundamental package for scientific computing in python
- **Pandas** - an ease-to-use python library for manipulating data structures and performing data analysis
- **Jupyter Notebook** - a tool that allow the creation of documents with live code
- **Matplotlib** - a plotting library for the Python programming language and its numerical mathematics extension NumPy.

## What you should already know

- neural networks,
- forward and back-propagation
- gradient descent

## Setup Instructions

Setup Instructions taken from [here](https://classroom.udacity.com/nanodegrees/nd101/parts/94643112-2cab-46f8-a5be-1b6e4fa7a211/modules/07d52f20-312f-448d-9980-71d162caa76e/lessons/2ced92c6-f377-4d29-b5aa-8e887f1e4a6f/project)

In a nutshell:

1. Install [Anaconda](https://www.anaconda.com/distribution/).
2. Download the project
3. cd into the project folder
4. Run the code below to create and activate new environment

```
conda create --name bike_sharing_proj_env
```

- Mac/Linux:

```
source activate bike_sharing_proj_env 
```

- Windows:

```
activate bike_sharing_proj_env
```

```
conda install numpy pandas matplotlib
jupyter notebook
```

## Training & Validation Loss Graph

![alt text][image1]

![alt text][image2]

## Predictions Check Graph

![alt text][image3]
