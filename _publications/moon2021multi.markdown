---
layout: publication
title: Multi-modal Understanding And Generation For Medical Images And Text Via Vision-language
  Pre-training
authors: Moon et al.
conference: IEEE Journal of Biomedical and Health Informatics
year: 2021
bibkey: moon2021multi
citations: 129
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.11333'}]
tags: [Model Architecture, Training Techniques, BERT, ALT, Multimodal Models, Datasets,
  Attention Mechanism, Alt]
---
Recently a number of studies demonstrated impressive performance on diverse
vision-language multi-modal tasks such as image captioning and visual question
answering by extending the BERT architecture with multi-modal pre-training
objectives. In this work we explore a broad set of multi-modal representation
learning tasks in the medical domain, specifically using radiology images and
the unstructured report. We propose Medical Vision Language Learner (MedViLL),
which adopts a BERT-based architecture combined with a novel multi-modal
attention masking scheme to maximize generalization performance for both
vision-language understanding tasks (diagnosis classification, medical
image-report retrieval, medical visual question answering) and vision-language
generation task (radiology report generation). By statistically and rigorously
evaluating the proposed model on four downstream tasks with three radiographic
image-report datasets (MIMIC-CXR, Open-I, and VQA-RAD), we empirically
demonstrate the superior downstream task performance of MedViLL against various
baselines, including task-specific architectures. The source code is publicly
available at: https://github.com/SuperSupermoon/MedViLL