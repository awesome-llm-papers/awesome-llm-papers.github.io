---
layout: publication
title: The University Of Edinburgh's Neural MT Systems For WMT17
authors: Rico Sennrich, Alexandra Birch, Anna Currey, Ulrich Germann, Barry Haddow,
  Kenneth Heafield, Antonio Valerio Miceli Barone, Philip Williams
conference: Proceedings of the Second Conference on Machine Translation
year: 2017
bibkey: sennrich2017university
citations: 161
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.00726'}]
tags: ["Training Techniques"]
short_authors: Sennrich et al.
---
This paper describes the University of Edinburgh's submissions to the WMT17
shared news translation and biomedical translation tasks. We participated in 12
translation directions for news, translating between English and Czech, German,
Latvian, Russian, Turkish and Chinese. For the biomedical task we submitted
systems for English to Czech, German, Polish and Romanian. Our systems are
neural machine translation systems trained with Nematus, an attentional
encoder-decoder. We follow our setup from last year and build BPE-based models
with parallel and back-translated monolingual training data. Novelties this
year include the use of deep architectures, layer normalization, and more
compact models due to weight tying and improvements in BPE segmentations. We
perform extensive ablative experiments, reporting on the effectivenes of layer
normalization, deep architectures, and different ensembling techniques.