---
layout: publication
title: Capturing Failures Of Large Language Models Via Human Cognitive Biases
authors: Erik Jones, Jacob Steinhardt
conference: Arxiv
year: 2022
citations: 30
bibkey: jones2022capturing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.12299'}]
tags: [Ethics and Bias, Tools, Training Techniques, Prompting]
---
Large language models generate complex, open-ended outputs: instead of
outputting a class label they write summaries, generate dialogue, or produce
working code. In order to asses the reliability of these open-ended generation
systems, we aim to identify qualitative categories of erroneous behavior,
beyond identifying individual errors. To hypothesize and test for such
qualitative errors, we draw inspiration from human cognitive biases --
systematic patterns of deviation from rational judgement. Specifically, we use
cognitive biases as motivation to (i) generate hypotheses for problems that
models may have, and (ii) develop experiments that elicit these problems. Using
code generation as a case study, we find that OpenAI's Codex errs predictably
based on how the input prompt is framed, adjusts outputs towards anchors, and
is biased towards outputs that mimic frequent training examples. We then use
our framework to elicit high-impact errors such as incorrectly deleting files.
Our results indicate that experimental methodology from cognitive science can
help characterize how machine learning systems behave.