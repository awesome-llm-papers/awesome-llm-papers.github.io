---
layout: publication
title: 'RT-2: Vision-language-action Models Transfer Web Knowledge To Robotic Control'
authors: Anthony Brohan et al.
conference: Arxiv
year: 2023
citations: 120
bibkey: brohan2023rt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.15818'}]
tags: [Training Techniques, Multimodal Models, Evaluation]
---
We study how vision-language models trained on Internet-scale data can be
incorporated directly into end-to-end robotic control to boost generalization
and enable emergent semantic reasoning. Our goal is to enable a single
end-to-end trained model to both learn to map robot observations to actions and
enjoy the benefits of large-scale pretraining on language and vision-language
data from the web. To this end, we propose to co-fine-tune state-of-the-art
vision-language models on both robotic trajectory data and Internet-scale
vision-language tasks, such as visual question answering. In contrast to other
approaches, we propose a simple, general recipe to achieve this goal: in order
to fit both natural language responses and robotic actions into the same
format, we express the actions as text tokens and incorporate them directly
into the training set of the model in the same way as natural language tokens.
We refer to such category of models as vision-language-action models (VLA) and
instantiate an example of such a model, which we call RT-2. Our extensive
evaluation (6k evaluation trials) shows that our approach leads to performant
robotic policies and enables RT-2 to obtain a range of emergent capabilities
from Internet-scale training. This includes significantly improved
generalization to novel objects, the ability to interpret commands not present
in the robot training data (such as placing an object onto a particular number
or icon), and the ability to perform rudimentary reasoning in response to user
commands (such as picking up the smallest or largest object, or the one closest
to another object). We further show that incorporating chain of thought
reasoning allows RT-2 to perform multi-stage semantic reasoning, for example
figuring out which object to pick up for use as an improvised hammer (a rock),
or which type of drink is best suited for someone who is tired (an energy
drink).