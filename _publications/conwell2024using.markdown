---
layout: publication
title: Using Multimodal Deep Neural Networks To Disentangle Language From Visual Aesthetics
authors: Conwell et al.
conference: IEEE Transactions on Emerging Topics in Computational Intelligence
year: 2024
bibkey: conwell2024using
citations: 183
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.23603'}]
tags: [Model Architecture, Multimodal Models, Merging, GPT]
---
When we experience a visual stimulus as beautiful, how much of that
experience derives from perceptual computations we cannot describe versus
conceptual knowledge we can readily translate into natural language?
Disentangling perception from language in visually-evoked affective and
aesthetic experiences through behavioral paradigms or neuroimaging is often
empirically intractable. Here, we circumnavigate this challenge by using linear
decoding over the learned representations of unimodal vision, unimodal
language, and multimodal (language-aligned) deep neural network (DNN) models to
predict human beauty ratings of naturalistic images. We show that unimodal
vision models (e.g. SimCLR) account for the vast majority of explainable
variance in these ratings. Language-aligned vision models (e.g. SLIP) yield
small gains relative to unimodal vision. Unimodal language models (e.g. GPT2)
conditioned on visual embeddings to generate captions (via CLIPCap) yield no
further gains. Caption embeddings alone yield less accurate predictions than
image and caption embeddings combined (concatenated). Taken together, these
results suggest that whatever words we may eventually find to describe our
experience of beauty, the ineffable computations of feedforward perception may
provide sufficient foundation for that experience.