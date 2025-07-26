---
layout: publication
title: Grounding Visual Explanations
authors: Lisa Anne Hendricks, Ronghang Hu, Trevor Darrell, Zeynep Akata
conference: Lecture Notes in Computer Science
year: 2018
bibkey: hendricks2018grounding
citations: 204
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.09685'}]
tags: ["Agentic", "Datasets", "Training Techniques"]
short_authors: Hendricks et al.
---
Existing visual explanation generating agents learn to fluently justify a
class prediction. However, they may mention visual attributes which reflect a
strong class prior, although the evidence may not actually be in the image.
This is particularly concerning as ultimately such agents fail in building
trust with human users. To overcome this limitation, we propose a phrase-critic
model to refine generated candidate explanations augmented with flipped phrases
which we use as negative examples while training. At inference time, our
phrase-critic model takes an image and a candidate explanation as input and
outputs a score indicating how well the candidate explanation is grounded in
the image. Our explainable AI agent is capable of providing counter arguments
for an alternative prediction, i.e. counterfactuals, along with explanations
that justify the correct classification decisions. Our model improves the
textual explanation quality of fine-grained classification decisions on the CUB
dataset by mentioning phrases that are grounded in the image. Moreover, on the
FOIL tasks, our agent detects when there is a mistake in the sentence, grounds
the incorrect phrase and corrects it significantly better than other models.