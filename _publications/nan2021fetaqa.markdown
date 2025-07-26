---
layout: publication
title: 'Fetaqa: Free-form Table Question Answering'
authors: "Linyong Nan, Chiachun Hsieh, Ziming Mao, Xi Victoria Lin, Neha Verma, Rui\
  \ Zhang, Wojciech Kry\u015Bci\u0144ski, Nick Schoelkopf, Riley Kong, Xiangru Tang,\
  \ Murori Mutuma, Ben Rosand, Isabel Trindade, Renusree Bandaru, Jacob Cunningham,\
  \ Caiming Xiong, Dragomir Radev"
conference: Transactions of the Association for Computational Linguistics
year: 2022
bibkey: nan2021fetaqa
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.00369'}]
tags: ["TACL"]
short_authors: Nan et al.
---
Existing table question answering datasets contain abundant factual questions
that primarily evaluate the query and schema comprehension capability of a
system, but they fail to include questions that require complex reasoning and
integration of information due to the constraint of the associated short-form
answers. To address these issues and to demonstrate the full challenge of table
question answering, we introduce FeTaQA, a new dataset with 10K Wikipedia-based
\{table, question, free-form answer, supporting table cells\} pairs. FeTaQA
yields a more challenging table question answering setting because it requires
generating free-form text answers after retrieval, inference, and integration
of multiple discontinuous facts from a structured knowledge source. Unlike
datasets of generative QA over text in which answers are prevalent with copies
of short text spans from the source, answers in our dataset are human-generated
explanations involving entities and their high-level relations. We provide two
benchmark methods for the proposed task: a pipeline method based on
semantic-parsing-based QA systems and an end-to-end method based on large
pretrained text generation models, and show that FeTaQA poses a challenge for
both methods.