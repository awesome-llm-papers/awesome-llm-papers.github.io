---
layout: publication
title: 'Tabert: Pretraining For Joint Understanding Of Textual And Tabular Data'
authors: Pengcheng Yin, Graham Neubig, Wen-tau Yih, Sebastian Riedel
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: yin2020tabert
citations: 343
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.08314'}]
tags: ["Datasets"]
short_authors: Yin et al.
---
Recent years have witnessed the burgeoning of pretrained language models
(LMs) for text-based natural language (NL) understanding tasks. Such models are
typically trained on free-form NL text, hence may not be suitable for tasks
like semantic parsing over structured data, which require reasoning over both
free-form NL questions and structured tabular data (e.g., database tables). In
this paper we present TaBERT, a pretrained LM that jointly learns
representations for NL sentences and (semi-)structured tables. TaBERT is
trained on a large corpus of 26 million tables and their English contexts. In
experiments, neural semantic parsers using TaBERT as feature representation
layers achieve new best results on the challenging weakly-supervised semantic
parsing benchmark WikiTableQuestions, while performing competitively on the
text-to-SQL dataset Spider. Implementation of the model will be available at
http://fburl.com/TaBERT .