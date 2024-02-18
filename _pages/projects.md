---
layout: page
permalink: /projects/
title: Projects
description: 
nav: true
nav_order: 2
---

I take part in ideation and development parts of following projects for my education, professional job and as a personal interest. I kindly encourage you to <a href = "mailto: anil.kults@gmail.com"><b>reach out</b></a> and engage in further discussion.

<div class="projects">

# Generative AI Projects

## Data Source Specific Chatbot

A Chatbot that can answer questions only according to provided data source.

- **Techstack:** React, FastAPI, Python, OpenAI API (Function Calling)

![alt text](https://github.com/anilkul98/anilkul98.github.io/assets/project/chatbot.png?raw=true)


## Text-guided 3D Object Manipulation

A pretrained deepSDF 3D Shape generator model is used to generate 3D Shapes. CLIP model is used for text-guide mechanism. 2D Images of 3D objects are given to the CLIP to get feedback. See <a href="https://github.com/anilkul98/3d-text-guided-manipulation" >GitHub</a> repository.


![alt text](https://github.com/anilkul98/anilkul98.github.io/assets/project/3d.png?raw=true)

# Computer Vision Projects

## Acute Otitis Media Diagnose

The aim of the project is diagnosing the acute otitis media disease from the otoscope videos. It is a video classification task. MobileNet V2 is used as image feature extractor and LSTM with attention is used to extract information from temporal domain.

![alt text](https://github.com/anilkul98/anilkul98.github.io/assets/project/acute_otisis_media.png?raw=true)

## Biodiversity Detection From Satellite Images

The main aim of the project is detecting high biodiversity areas of North of the Sweden by using the high biodiversity areas of the South of Sweden. The problem is a segmentation problem, so the output is pixelwise detection of high biodiversity areas. UNet is used as an image segmentation network.

![alt text](https://github.com/anilkul98/anilkul98.github.io/assets/project/biodiversity.png?raw=true)

## Tooth Decay Diagnose

The aim of the project is detecting the tooth decay areas on the bitewing X-rays. After detecting tooths from bitewing image, image classifier is applied on it to detect whether the teeth is decayed or not. Also, with using class activation maps, it is also possible to locate the decayed areas probabilities on the tooth.


![alt text](https://github.com/anilkul98/anilkul98.github.io/assets/project/tooth_decay.png?raw=true)

## Multiple Object Tracking

Tracking the multiple humans in videos. MOT16 dataset is used for implementation.


![alt text](https://github.com/anilkul98/anilkul98.github.io/assets/project/mot.png?raw=true)

# Time Series Prediction Projects

## Next Action Prediction

It is a simple time series prediction implementation. The main aim is predicting the next action of the user in terms of mouse position and the action on the screen. Basic LSTM is used as a model and trained by action logs of real users.


