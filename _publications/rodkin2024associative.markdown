---
layout: publication
title: Associative Recurrent Memory Transformer
authors: Ivan Rodkin, Yuri Kuratov, Aydar Bulatov, Mikhail Burtsev
conference: No Venue
year: 2024
bibkey: rodkin2024associative
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/668cee03f8e6657dff5baf2b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.04841'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Rodkin et al.
---
This paper addresses the challenge of creating a neural architecture for very long sequences that requires constant time for processing new information at each time step. Our approach, Associative Recurrent Memory Transformer (ARMT), is based on transformer self-attention for local context and segment-level recurrence for storage of task specific information distributed over a long context. We demonstrate that ARMT outperfors existing alternatives in associative retrieval tasks and sets a new performance record in the recent BABILong multi-task long-context benchmark by answering single-fact questions over 50 million tokens with an accuracy of 79.9%. The source code for training and evaluation is available on github.

https://huggingface.co/discussions/paper/668cee03f8e6657dff5baf2b