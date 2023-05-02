# Pizza-Classification-Using-ANN


## Table of Contents
- [Overview](#Overview)
- [Problem Statement](#Problem-Statement)
- [Methodology](#Methodology)
- [Technologies Used](#Technologies-Used)
- [Results](#Result)

## Overview
A famous 30 year old pizza brand which has outlets in more than 90 countries started home
delivery services a couple of years ago and the business has grown much faster than expected.
However, outlet vendors are very much disappointed with few customers for their cheating
activities. This is because vendors, shockingly, came to know that few customers after receiving the
delivery are raising tickets for refund in the name of burnt pizzas. Even though customers received
a good pizza but still few customers are trying to cheat vendors. To overcome this issue, Franchise
has come up with an idea to integrate a pizza detection model in their application where customers
can upload images for the burnt pizzas delivered. For example, if I have received a burnt pizza then
I can upload a couple of images of the pizza to the application and it will classify the pizza as burnt
or good in order to process my refund ticket.

## Problem Statement
You are hired as Deep Learning Engineer by a famous pizza franchise. You are asked to build a model where it accepts the images of pizza and detects as burnt pizza or good pizza.
You should be using only ANN and shouldn’t be using CNN or any other rule based model to generate results. Data is in the form of images collected from multiple sources of the internet.
Train set is divided into burnt pizza and good pizza categories. While training the model you can label images of good pizza as 1 and burnt pizza as 0. Test set contains mixed images of both burnt pizzas and good pizzas.

## Methodology
- Used Image Data Generator to get the data from the folders.
- Used Transfer Learning (VGG16) for classification.

## Technologies Used
[![Made withGoogleColab](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Results
![image]("C:\Users\HP\Downloads\Gradio Pizza.png")
