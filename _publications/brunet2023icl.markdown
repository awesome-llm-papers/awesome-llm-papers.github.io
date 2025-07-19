---
layout: publication
title: 'ICL Markup: Structuring In-context Learning Using Soft-token Tags'
authors: Brunet Marc-etienne, Anderson Ashton, Zemel Richard
conference: Proceedings of the 24th annual international ACM SIGIR conference on Research
  and development in information retrieval
year: 2023
bibkey: brunet2023icl
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.07405'}]
tags: [Training Techniques, Prompting, Tools, In Context Learning, Few Shot, Reinforcement
    Learning, SIGIR, Applications, Fine Tuning]
---
Large pretrained language models (LLMs) can be rapidly adapted to a wide
variety of tasks via a text-to-text approach, where the instruction and input
are fed to the model in natural language. Combined with in-context learning
(ICL), this paradigm is impressively flexible and powerful. However, it also
burdens users with an overwhelming number of choices, many of them arbitrary.
Inspired by markup languages like HTML, we contribute a method of using
soft-token tags to compose prompt templates. This approach reduces arbitrary
decisions and streamlines the application of ICL. Our method is a form of
meta-learning for ICL; it learns these tags in advance during a
parameter-efficient fine-tuning ``warm-up'' process. The tags can subsequently
be used in templates for ICL on new, unseen tasks without any additional
fine-tuning. Our experiments with this approach yield promising initial
results, improving LLM performance on important enterprise applications such as
few-shot and open-world intent detection, as well as text classification in
news and legal domains.