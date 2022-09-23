# Image_Classification_Talent_Squad_DS 


# Talent Squad - Data Science II
--------

## Quick Start

This project was done in a Jupyter Notebook but the model training was done from google Colab since they offer free GPUs and TPUs[^1] in case you want to save some time :wink:.

* <a href="https://colab.research.google.com/github/Freegalado/NoSupervisat_Agrupament/blob/main/S11_T01_Unsupervised_Learning_Grouping.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

if you want to open it in locally don't forget to have installed:

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)



--------
## Table of Contents

- [Description](#description)
- [Decision-making process](#decision-making-process)




### Description 

The project consists of classifying the different images by the type of sport to which they correspond, with the following: baseball, cricket and football.

The labels we will have for each group of images will be in alphabetical order, as follows:  

    - Baseball will be represented with the digit 0.

    - Cricket will be represented with the digit 1.

    - Football will be represented with the digit 2.


**The evaluation objectives will be:**

    1. Increase of samples in the images. 

    2. Calculate the macro F1-score. 

    
  #### [top](#table-of-contents)
--------

 ### Decision-making process
  

We have a classification problem so it is appropriate to use an Artificial neural networks (ANNs) with this we can detect patterns and use them to solve problems where we have to detect patterns. ANNs are composed of a layer of nodes, which contains an input layer, one more hidden layers and an output layer, each node is connected to another letting information pass to a greater or lesser extent depending on the final prediction, the values that indicate the level at which they let the information pass are called weights. 

 

For the solution of our problem we will use a convolutional neural network (CNNs), the difference is that a new mathematical operation is introduced.
called convolution. This new operation is the one that will allow us to find patterns in the images, and it is these patterns that are later used to solve our classification problem.

  #### [top](#table-of-contents)
--------




--------
![Diagrama sin título-Página-1 drawio-2](https://user-images.githubusercontent.com/91080406/191446222-c717a553-9b0b-47d8-a413-18b2321b33ec.png)

---------


 

[^1]: In order to offer computational resources at no cost, Colab needs to retain the flexibility to adjust usage limits and hardware availability at any time 
