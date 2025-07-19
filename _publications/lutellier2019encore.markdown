---
layout: publication
title: 'ENCORE: Ensemble Learning Using Convolution Neural Machine Translation For
  Automatic Program Repair'
authors: Lutellier et al.
conference: 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE)
year: 2019
bibkey: lutellier2019encore
citations: 217
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.08691'}]
tags: [Model Architecture, LLM For Code, Evaluation, LLM for Code, Datasets]
---
Automated generate-and-validate (G&V) program repair techniques typically
rely on hard-coded rules, only fix bugs following specific patterns, and are
hard to adapt to different programming languages. We propose ENCORE, a new G&V
technique, which uses ensemble learning on convolutional neural machine
translation (NMT) models to automatically fix bugs in multiple programming
languages.
  We take advantage of the randomness in hyper-parameter tuning to build
multiple models that fix different bugs and combine them using ensemble
learning. This new convolutional NMT approach outperforms the standard long
short-term memory (LSTM) approach used in previous work, as it better captures
both local and long-distance connections between tokens.
  Our evaluation on two popular benchmarks, Defects4J and QuixBugs, shows that
ENCORE fixed 42 bugs, including 16 that have not been fixed by existing
techniques. In addition, ENCORE is the first G&V repair technique to be applied
to four popular programming languages (Java, C++, Python, and JavaScript),
fixing a total of 67 bugs across five benchmarks.