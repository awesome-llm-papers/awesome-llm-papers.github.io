---
layout: publication
title: Speech Model Pre-training For End-to-end Spoken Language Understanding
authors: Loren Lugosch, Mirco Ravanelli, Patrick Ignoto, Vikrant Singh Tomar, Yoshua
  Bengio
conference: Interspeech 2019
year: 2019
bibkey: lugosch2019speech
citations: 241
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.03670'}]
tags: ["INTERSPEECH", "Training Techniques"]
short_authors: Lugosch et al.
---
Whereas conventional spoken language understanding (SLU) systems map speech
to text, and then text to intent, end-to-end SLU systems map speech directly to
intent through a single trainable model. Achieving high accuracy with these
end-to-end models without a large amount of training data is difficult. We
propose a method to reduce the data requirements of end-to-end SLU in which the
model is first pre-trained to predict words and phonemes, thus learning good
features for SLU. We introduce a new SLU dataset, Fluent Speech Commands, and
show that our method improves performance both when the full dataset is used
for training and when only a small subset is used. We also describe preliminary
experiments to gauge the model's ability to generalize to new phrases not heard
during training.