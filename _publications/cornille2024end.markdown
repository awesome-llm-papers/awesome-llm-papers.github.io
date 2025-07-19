---
layout: publication
title: End-to-end Planner Training For Language Modeling
authors: Cornille et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: cornille2024end
citations: 255
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.12492'}]
tags: [RAG, Training Techniques, Tools, CVPR, Language Modeling, Applications, Fine
    Tuning]
---
Through end-to-end training to predict the next token, LLMs have become
valuable tools for various tasks. Enhancing their core training in language
modeling can improve numerous downstream applications. A successful approach to
enhance language modeling uses a separate planning module to predict abstract
labels of future sentences and conditions the LM on these predictions. However,
this method is non-differentiable, preventing joint end-to-end tuning of the
planner with the LM. We propose an effective method to improve this approach by
enabling joint fine-tuning of the planner and the LM. We show that a naive way
of approximating the gradient of selecting a label via the straight-through
estimator is not effective. Instead, we propose to use the predicted label
probabilities as mixing weights to condition the LM on a weighted average of
label embeddings in a differentiable manner. This not only enables joint
fine-tuning of the planner and the LM, but also allows the LM to draw on the
full label distribution predicted by the planner, retaining more information.
Our experimental results show consistent improvements in perplexity.