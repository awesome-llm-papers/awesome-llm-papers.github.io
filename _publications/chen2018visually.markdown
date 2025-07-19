---
layout: publication
title: Visually Explainable Recommendation
authors: Chen et al.
conference: Proceedings of the 30th ACM International Conference on Information &amp;
  Knowledge Management
year: 2018
bibkey: chen2018visually
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.10288'}]
tags: [Model Architecture, Interpretability And Explainability, Attention Mechanism,
  CIKM]
---
Images account for a significant part of user decisions in many application
scenarios, such as product images in e-commerce, or user image posts in social
networks. It is intuitive that user preferences on the visual patterns of image
(e.g., hue, texture, color, etc) can be highly personalized, and this provides
us with highly discriminative features to make personalized recommendations.
  Previous work that takes advantage of images for recommendation usually
transforms the images into latent representation vectors, which are adopted by
a recommendation component to assist personalized user/item profiling and
recommendation. However, such vectors are hardly useful in terms of providing
visual explanations to users about why a particular item is recommended, and
thus weakens the explainability of recommendation systems.
  As a step towards explainable recommendation models, we propose visually
explainable recommendation based on attentive neural networks to model the user
attention on images, under the supervision of both implicit feedback and
textual reviews. By this, we can not only provide recommendation results to the
users, but also tell the users why an item is recommended by providing
intuitive visual highlights in a personalized manner. Experimental results show
that our models are not only able to improve the recommendation performance,
but also can provide persuasive visual explanations for the users to take the
recommendations.