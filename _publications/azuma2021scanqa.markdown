---
layout: publication
title: 'Scanqa: 3D Question Answering For Spatial Scene Understanding'
authors: Daichi Azuma, Taiki Miyanishi, Shuhei Kurita, Motoaki Kawanabe
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: azuma2021scanqa
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.10482'}]
tags: ["CVPR", "Datasets"]
short_authors: Azuma et al.
---
We propose a new 3D spatial understanding task of 3D Question Answering
(3D-QA). In the 3D-QA task, models receive visual information from the entire
3D scene of the rich RGB-D indoor scan and answer the given textual questions
about the 3D scene. Unlike the 2D-question answering of VQA, the conventional
2D-QA models suffer from problems with spatial understanding of object
alignment and directions and fail the object identification from the textual
questions in 3D-QA. We propose a baseline model for 3D-QA, named ScanQA model,
where the model learns a fused descriptor from 3D object proposals and encoded
sentence embeddings. This learned descriptor correlates the language
expressions with the underlying geometric features of the 3D scan and
facilitates the regression of 3D bounding boxes to determine described objects
in textual questions and outputs correct answers. We collected human-edited
question-answer pairs with free-form answers that are grounded to 3D objects in
each 3D scene. Our new ScanQA dataset contains over 40K question-answer pairs
from the 800 indoor scenes drawn from the ScanNet dataset. To the best of our
knowledge, the proposed 3D-QA task is the first large-scale effort to perform
object-grounded question-answering in 3D environments.