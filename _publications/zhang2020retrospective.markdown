---
layout: publication
title: Retrospective Reader For Machine Reading Comprehension
authors: Zhuosheng Zhang, Junjie Yang, Hai Zhao
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: zhang2020retrospective
citations: 187
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.09694'}]
tags: ["AAAI", "Evaluation"]
short_authors: Zhuosheng Zhang, Junjie Yang, Hai Zhao
---
Machine reading comprehension (MRC) is an AI challenge that requires machine
to determine the correct answers to questions based on a given passage. MRC
systems must not only answer question when necessary but also distinguish when
no answer is available according to the given passage and then tactfully
abstain from answering. When unanswerable questions are involved in the MRC
task, an essential verification module called verifier is especially required
in addition to the encoder, though the latest practice on MRC modeling still
most benefits from adopting well pre-trained language models as the encoder
block by only focusing on the "reading". This paper devotes itself to exploring
better verifier design for the MRC task with unanswerable questions. Inspired
by how humans solve reading comprehension questions, we proposed a
retrospective reader (Retro-Reader) that integrates two stages of reading and
verification strategies: 1) sketchy reading that briefly investigates the
overall interactions of passage and question, and yield an initial judgment; 2)
intensive reading that verifies the answer and gives the final prediction. The
proposed reader is evaluated on two benchmark MRC challenge datasets SQuAD2.0
and NewsQA, achieving new state-of-the-art results. Significance tests show
that our model is significantly better than the strong ELECTRA and ALBERT
baselines. A series of analysis is also conducted to interpret the
effectiveness of the proposed reader.