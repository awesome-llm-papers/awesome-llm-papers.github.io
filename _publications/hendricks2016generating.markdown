---
layout: publication
title: Generating Visual Explanations
authors: Lisa Anne Hendricks, Zeynep Akata, Marcus Rohrbach, Jeff Donahue, Bernt Schiele,
  Trevor Darrell
conference: Lecture Notes in Computer Science
year: 2016
bibkey: hendricks2016generating
citations: 498
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.08507'}]
tags: ["Datasets", "Reinforcement Learning"]
short_authors: Hendricks et al.
---
Clearly explaining a rationale for a classification decision to an end-user
can be as important as the decision itself. Existing approaches for deep visual
recognition are generally opaque and do not output any justification text;
contemporary vision-language models can describe image content but fail to take
into account class-discriminative image aspects which justify visual
predictions. We propose a new model that focuses on the discriminating
properties of the visible object, jointly predicts a class label, and explains
why the predicted label is appropriate for the image. We propose a novel loss
function based on sampling and reinforcement learning that learns to generate
sentences that realize a global sentence property, such as class specificity.
Our results on a fine-grained bird species classification dataset show that our
model is able to generate explanations which are not only consistent with an
image but also more discriminative than descriptions produced by existing
captioning methods.