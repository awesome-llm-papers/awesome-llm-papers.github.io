---
layout: publication
title: 'Medicalnarratives: Connecting Medical Vision And Language With Localized Narratives'
authors: Ikezogwo et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: ikezogwo2025medicalnarratives
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.04184'}]
tags: [Model Architecture, Training Techniques, Evaluation, Datasets]
---
We propose MedicalNarratives, a dataset curated from medical pedagogical
videos similar in nature to data collected in Think-Aloud studies and inspired
by Localized Narratives, which collects grounded image-text data by curating
instructors' speech and mouse cursor movements synchronized in time.
MedicalNarratives enables pretraining of both semantic and dense objectives,
alleviating the need to train medical semantic and dense tasks disparately due
to the lack of reasonably sized datasets. Our dataset contains 4.7M image-text
pairs from videos and articles, with 1M samples containing dense annotations in
the form of traces and bounding boxes. To evaluate the utility of
MedicalNarratives, we train GenMedClip based on the CLIP architecture using our
dataset spanning 12 medical domains and demonstrate that it outperforms
previous state-of-the-art models on a newly constructed medical imaging
benchmark that comprehensively evaluates performance across all modalities.
Data, demo, code and models available at https://medical-narratives.github.io