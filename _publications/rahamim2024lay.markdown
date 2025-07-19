---
layout: publication
title: 'Lay-a-scene: Personalized 3D Object Arrangement Using Text-to-image Priors'
authors: Rahamim et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: rahamim2024lay
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.00687'}]
tags: [RAG]
---
Generating 3D visual scenes is at the forefront of visual generative AI, but
current 3D generation techniques struggle with generating scenes with multiple
high-resolution objects. Here we introduce Lay-A-Scene, which solves the task
of Open-set 3D Object Arrangement, effectively arranging unseen objects. Given
a set of 3D objects, the task is to find a plausible arrangement of these
objects in a scene. We address this task by leveraging pre-trained
text-to-image models. We personalize the model and explain how to generate
images of a scene that contains multiple predefined objects without neglecting
any of them. Then, we describe how to infer the 3D poses and arrangement of
objects from a 2D generated image by finding a consistent projection of objects
onto the 2D scene. We evaluate the quality of Lay-A-Scene using 3D objects from
Objaverse and human raters and find that it often generates coherent and
feasible 3D object arrangements.