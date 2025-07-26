---
layout: publication
title: 'Imojie: Iterative Memory-based Joint Open Information Extraction'
authors: Keshav Kolluru, Samarth Aggarwal, Vipul Rathore, Mausam, Soumen Chakrabarti
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: kolluru2020imojie
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.08178'}]
tags: ["Model Architecture"]
short_authors: Kolluru et al.
---
While traditional systems for Open Information Extraction were statistical
and rule-based, recently neural models have been introduced for the task. Our
work builds upon CopyAttention, a sequence generation OpenIE model (Cui et.
al., 2018). Our analysis reveals that CopyAttention produces a constant number
of extractions per sentence, and its extracted tuples often express redundant
information.
  We present IMoJIE, an extension to CopyAttention, which produces the next
extraction conditioned on all previously extracted tuples. This approach
overcomes both shortcomings of CopyAttention, resulting in a variable number of
diverse extractions per sentence. We train IMoJIE on training data bootstrapped
from extractions of several non-neural systems, which have been automatically
filtered to reduce redundancy and noise. IMoJIE outperforms CopyAttention by
about 18 F1 pts, and a BERT-based strong baseline by 2 F1 pts, establishing a
new state of the art for the task.