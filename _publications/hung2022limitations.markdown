---
layout: publication
title: On The Limitations Of Sociodemographic Adaptation With Transformers
authors: Hung et al.
conference: IEEE Journal of Biomedical and Health Informatics
year: 2022
bibkey: hung2022limitations
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.01029'}]
tags: [Model Architecture, ALT, Transformer, Language Modeling, Alt]
---
Sociodemographic factors (e.g., gender or age) shape our language. Previous
work showed that incorporating specific sociodemographic factors can
consistently improve performance for various NLP tasks in traditional NLP
models. We investigate whether these previous findings still hold with
state-of-the-art pretrained Transformers. We use three common specialization
methods proven effective for incorporating external knowledge into pretrained
Transformers (e.g., domain-specific or geographic knowledge). We adapt the
language representations for the sociodemographic dimensions of gender and age,
using continuous language modeling and dynamic multi-task learning for
adaptation, where we couple language modeling with the prediction of a
sociodemographic class. Our results when employing a multilingual model show
substantial performance gains across four languages (English, German, French,
and Danish). These findings are in line with the results of previous work and
hold promise for successful sociodemographic specialization. However,
controlling for confounding factors like domain and language shows that, while
sociodemographic adaptation does improve downstream performance, the gains do
not always solely stem from sociodemographic knowledge. Our results indicate
that sociodemographic specialization, while very important, is still an
unresolved problem in NLP.