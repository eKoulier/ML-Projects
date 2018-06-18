<img src="logo.png" width="400"/>

# ML-Projects

Here I have my projects for the [Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t) offered 
by [Udacity](https://eu.udacity.com/). You may find my certificate for this Nanodegree [here](https://graduation.udacity.com/confirm/FUNWY223).

## Transfer Learning for Dog Breed Classification

This project is related to Transfer Learning. I had to develop an algorithm that given a picture of a dog, it returns its breed. If there 
is a human in a picture the algorithm understands it, and then it tries to find the dog breed that he mostly resembles with. For this project 
I used some famous pretrained network architectures and compared them with my implementation. These architectures are the VGG16 introduced in 
[this paper](https://arxiv.org/abs/1409.1556) in 2014 and the ResNet-50 introduced in [this paper](https://arxiv.org/abs/1512.03385) in 2015. 
My end solution uses the later architecture with some modifications and its accuracy was 84%.


## Classifying the White Wine Quality Dataset

This is the Captstone one. It was a challenging classification task: Given a few physiochemical characteristics of a white wine, 
I developed an algorithm that predicts its quality. I had to design the complete pipeline of the project: from analysing the data 
to get initial insights to deliver a final model that classifies the quality of the white wine. This repository contains the project 
proposal I had to submit to Udacity, my code implementation and the final report where I present my results. I used [LaTeX](https://www.latex-project.org/) 
to write this report.

## Finding Donors for CharityML

In this project I had to develop an algorithm that accurately predicts whether an individual makes more than $50,000 thus he/she is willing 
to donate to CharityML (a fictional organization). I employed several supervised algorithms and I fine tuned the one that had the best 
performance. Several details were taken care of: The data was highly skewed, thus selecting the right metric took place. Apart from that, 
the other challenge was the fact that the data was mixed and included nominal, categorical and continous variables.

## Train a Smartcab to Drive

In this project I apply reinforcement learning techniques for a self-driving agent in a simplified world to aid it in 
effectively reaching its destinations in the allotted time. I investigate the environment the agent operates in by constructing  
a basic driving implementation. I then identify each possible state the agent can be in when considering such things as traffic lights 
and oncoming traffic at each intersection. With states identified, I then implement a Q-Learning algorithm for the self-driving agent 
to guide it towards its destination within the allotted time. Finally, I improve upon the Q-Learning algorithm to find the best configuration 
of learning and exploration factors to ensure the self-driving agent is reaching its destinations with consistently positive results.

