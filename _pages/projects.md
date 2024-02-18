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

<a id=""><h2 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Generative AI Projects</b></h2></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">


<a id="fact_aware"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Data Source Specific Chatbot</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

A Chatbot that can answer questions only according to provided data source.

<b>Techstack:</b> React, FastAPI, Python, OpenAI API (Function Calling)

[![Preview](assets/project/chatbot.png)](https://anilkul98.github.io)

<a id="3d"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Text-guided 3D Object Manipulation</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

A pretrained deepSDF 3D Shape generator model is used to generate 3D Shapes. CLIP model is used for text-guide mechanism. 2D Images of 3D objects are given to the CLIP to get feedback. See <a href="https://github.com/anilkul98/3d-text-guided-manipulation" >GitHub</a> repository.
</div>

[![Preview](assets/project/3d.png)](https://anilkul98.github.io)

<a id=""><h2 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Computer Vision Projects</b></h2></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">


<a id="3d"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Acute Otitis Media Diagnose</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

The aim of the project is diagnosing the acute otitis media disease from the otoscope videos. It is a video classification task. MobileNet V2 is used as image feature extractor and LSTM with attention is used to extract information from temporal domain.
</div>

[![Preview](assets/project/acute_otisis_media.png)](https://anilkul98.github.io)


<a id="3d"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Biodiversity Detection From Satellite Images</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

The main aim of the project is detecting high biodiversity areas of North of the Sweden by using the high biodiversity areas of the South of Sweden. The problem is a segmentation problem, so the output is pixelwise detection of high biodiversity areas. UNet is used as an image segmentation network.
</div>

[![Preview](assets/project/biodiversity.png)](https://anilkul98.github.io)

<a id="3d"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Tooth Decay Diagnose</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

The aim of the project is detecting the tooth decay areas on the bitewing X-rays. After detecting tooths from bitewing image, image classifier is applied on it to detect whether the teeth is decayed or not. Also, with using class activation maps, it is also possible to locate the decayed areas probabilities on the tooth.
</div>

[![Preview](assets/project/tooth_decay.png)](https://anilkul98.github.io)

<a id="3d"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Multiple Object Tracking</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

Tracking the multiple humans in videos. MOT16 dataset is used for implementation.
</div>

[![Preview](assets/project/mot.png)](https://anilkul98.github.io)

<a id=""><h2 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Time Series Prediction Projects</b></h2></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

<a id="3d"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;"><b>Next Action Prediction</b></h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">

It is a simple time series prediction implementation. The main aim is predicting the next action of the user in terms of mouse position and the action on the screen. Basic LSTM is used as a model and trained by action logs of real users.
</div>
