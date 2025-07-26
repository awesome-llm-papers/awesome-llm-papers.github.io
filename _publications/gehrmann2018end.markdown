---
layout: publication
title: End-to-end Content And Plan Selection For Data-to-text Generation
authors: Sebastian Gehrmann, Falcon Z. Dai, Henry Elder, Alexander M. Rush
conference: Proceedings of the 11th International Conference on Natural Language Generation
year: 2018
bibkey: gehrmann2018end
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.04700'}]
tags: ["Training Techniques"]
short_authors: Gehrmann et al.
---
Learning to generate fluent natural language from structured data with neural
networks has become an common approach for NLG. This problem can be challenging
when the form of the structured data varies between examples. This paper
presents a survey of several extensions to sequence-to-sequence models to
account for the latent content selection process, particularly variants of copy
attention and coverage decoding. We further propose a training method based on
diverse ensembling to encourage models to learn distinct sentence templates
during training. An empirical evaluation of these techniques shows an increase
in the quality of generated text across five automated metrics, as well as
human evaluation.