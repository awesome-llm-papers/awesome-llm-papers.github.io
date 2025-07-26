---
layout: publication
title: Improving Neural Question Generation Using Answer Separation
authors: Yanghoon Kim, Hwanhee Lee, Joongbo Shin, Kyomin Jung
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: kim2018improving
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.02393'}]
tags: ["AAAI"]
short_authors: Kim et al.
---
Neural question generation (NQG) is the task of generating a question from a
given passage with deep neural networks. Previous NQG models suffer from a
problem that a significant proportion of the generated questions include words
in the question target, resulting in the generation of unintended questions. In
this paper, we propose answer-separated seq2seq, which better utilizes the
information from both the passage and the target answer. By replacing the
target answer in the original passage with a special token, our model learns to
identify which interrogative word should be used. We also propose a new module
termed keyword-net, which helps the model better capture the key information in
the target answer and generate an appropriate question. Experimental results
demonstrate that our answer separation method significantly reduces the number
of improper questions which include answers. Consequently, our model
significantly outperforms previous state-of-the-art NQG models.