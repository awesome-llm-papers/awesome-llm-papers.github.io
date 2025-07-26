---
layout: publication
title: Increasing Faithfulness In Knowledge-grounded Dialogue With Controllable Features
authors: Hannah Rashkin, David Reitter, Gaurav Singh Tomar, Dipanjan Das
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: rashkin2021increasing
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.06963'}]
tags: ["Evaluation"]
short_authors: Rashkin et al.
---
Knowledge-grounded dialogue systems are intended to convey information that
is based on evidence provided in a given source text. We discuss the challenges
of training a generative neural dialogue model for such systems that is
controlled to stay faithful to the evidence. Existing datasets contain a mix of
conversational responses that are faithful to selected evidence as well as more
subjective or chit-chat style responses. We propose different evaluation
measures to disentangle these different styles of responses by quantifying the
informativeness and objectivity. At training time, additional inputs based on
these evaluation measures are given to the dialogue model. At generation time,
these additional inputs act as stylistic controls that encourage the model to
generate responses that are faithful to the provided evidence. We also
investigate the usage of additional controls at decoding time using resampling
techniques. In addition to automatic metrics, we perform a human evaluation
study where raters judge the output of these controlled generation models to be
generally more objective and faithful to the evidence compared to baseline
dialogue systems.