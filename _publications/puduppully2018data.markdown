---
layout: publication
title: Data-to-text Generation With Content Selection And Planning
authors: Ratish Puduppully, Li Dong, Mirella Lapata
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: puduppully2018data
citations: 273
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.00582'}]
tags: ["AAAI", "Datasets", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Ratish Puduppully, Li Dong, Mirella Lapata
---
Recent advances in data-to-text generation have led to the use of large-scale
datasets and neural network models which are trained end-to-end, without
explicitly modeling what to say and in what order. In this work, we present a
neural network architecture which incorporates content selection and planning
without sacrificing end-to-end training. We decompose the generation task into
two stages. Given a corpus of data records (paired with descriptive documents),
we first generate a content plan highlighting which information should be
mentioned and in which order and then generate the document while taking the
content plan into account. Automatic and human-based evaluation experiments
show that our model outperforms strong baselines improving the state-of-the-art
on the recently released RotoWire dataset.