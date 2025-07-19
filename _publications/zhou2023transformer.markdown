---
layout: publication
title: A Transformer-based Representation-learning Model With Unified Processing Of
  Multimodal Input For Clinical Diagnostics
authors: Zhou et al.
conference: Nature Biomedical Engineering
year: 2023
bibkey: zhou2023transformer
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.00864'}]
tags: [RAG, Attention Mechanism, Transformer, Model Architecture, Multimodal Models]
---
During the diagnostic process, clinicians leverage multimodal information,
such as chief complaints, medical images, and laboratory-test results.
Deep-learning models for aiding diagnosis have yet to meet this requirement.
Here we report a Transformer-based representation-learning model as a clinical
diagnostic aid that processes multimodal input in a unified manner. Rather than
learning modality-specific features, the model uses embedding layers to convert
images and unstructured and structured text into visual tokens and text tokens,
and bidirectional blocks with intramodal and intermodal attention to learn a
holistic representation of radiographs, the unstructured chief complaint and
clinical history, structured clinical information such as laboratory-test
results and patient demographic information. The unified model outperformed an
image-only model and non-unified multimodal diagnosis models in the
identification of pulmonary diseases (by 12% and 9%, respectively) and in the
prediction of adverse clinical outcomes in patients with COVID-19 (by 29% and
7%, respectively). Leveraging unified multimodal Transformer-based models may
help streamline triage of patients and facilitate the clinical decision
process.