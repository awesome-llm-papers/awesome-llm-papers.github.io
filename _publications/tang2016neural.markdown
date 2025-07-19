---
layout: publication
title: Neural Machine Translation With External Phrase Memory
authors: Tang et al.
conference: Arxiv
year: 2016
bibkey: tang2016neural
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.01792'}]
tags: [Datasets]
---
In this paper, we propose phraseNet, a neural machine translator with a
phrase memory which stores phrase pairs in symbolic form, mined from corpus or
specified by human experts. For any given source sentence, phraseNet scans the
phrase memory to determine the candidate phrase pairs and integrates tagging
information in the representation of source sentence accordingly. The decoder
utilizes a mixture of word-generating component and phrase-generating
component, with a specifically designed strategy to generate a sequence of
multiple words all at once. The phraseNet not only approaches one step towards
incorporating external knowledge into neural machine translation, but also
makes an effort to extend the word-by-word generation mechanism of recurrent
neural network. Our empirical study on Chinese-to-English translation shows
that, with carefully-chosen phrase table in memory, phraseNet yields 3.45 BLEU
improvement over the generic neural machine translator.