---
layout: publication
title: 'Tracking State Changes In Procedural Text: A Challenge Dataset And Models
  For Process Paragraph Comprehension'
authors: Bhavana Dalvi Mishra, Lifu Huang, Niket Tandon, Wen-tau Yih, Peter Clark
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: mishra2018tracking
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.06975'}]
tags: ["Datasets", "Model Architecture", "NAACL"]
short_authors: Mishra et al.
---
We present a new dataset and models for comprehending paragraphs about
processes (e.g., photosynthesis), an important genre of text describing a
dynamic world. The new dataset, ProPara, is the first to contain natural
(rather than machine-generated) text about a changing world along with a full
annotation of entity states (location and existence) during those changes (81k
datapoints). The end-task, tracking the location and existence of entities
through the text, is challenging because the causal effects of actions are
often implicit and need to be inferred. We find that previous models that have
worked well on synthetic data achieve only mediocre performance on ProPara, and
introduce two new neural models that exploit alternative mechanisms for state
prediction, in particular using LSTM input encoding and span prediction. The
new models improve accuracy by up to 19%. The dataset and models are available
to the community at http://data.allenai.org/propara.