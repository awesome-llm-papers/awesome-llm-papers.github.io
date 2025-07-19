---
layout: publication
title: APE At Scale And Its Implications On MT Evaluation Biases
authors: Freitag Markus, Caswell Isaac, Roy Scott
conference: 'Proceedings of the Fourth Conference on Machine Translation (Volume 1:
  Research Papers)'
year: 2019
bibkey: freitag2019ape
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.04790'}]
tags: [Ethics And Bias, WMT, Evaluation]
---
In this work, we train an Automatic Post-Editing (APE) model and use it to
reveal biases in standard Machine Translation (MT) evaluation procedures. The
goal of our APE model is to correct typical errors introduced by the
translation process, and convert the "translationese" output into natural text.
Our APE model is trained entirely on monolingual data that has been round-trip
translated through English, to mimic errors that are similar to the ones
introduced by NMT. We apply our model to the output of existing NMT systems,
and demonstrate that, while the human-judged quality improves in all cases,
BLEU scores drop with forward-translated test sets. We verify these results for
the WMT18 English to German, WMT15 English to French, and WMT16 English to
Romanian tasks. Furthermore, we selectively apply our APE model on the output
of the top submissions of the most recent WMT evaluation campaigns. We see
quality improvements on all tasks of up to 2.5 BLEU points.