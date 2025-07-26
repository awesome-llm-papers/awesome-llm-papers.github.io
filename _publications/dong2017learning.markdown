---
layout: publication
title: Learning To Paraphrase For Question Answering
authors: Li Dong, Jonathan Mallinson, Siva Reddy, Mirella Lapata
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: dong2017learning
citations: 192
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.06022'}]
tags: ["Datasets", "EMNLP"]
short_authors: Dong et al.
---
Question answering (QA) systems are sensitive to the many different ways
natural language expresses the same information need. In this paper we turn to
paraphrases as a means of capturing this knowledge and present a general
framework which learns felicitous paraphrases for various QA tasks. Our method
is trained end-to-end using question-answer pairs as a supervision signal. A
question and its paraphrases serve as input to a neural scoring model which
assigns higher weights to linguistic expressions most likely to yield correct
answers. We evaluate our approach on QA over Freebase and answer sentence
selection. Experimental results on three datasets show that our framework
consistently improves performance, achieving competitive results despite the
use of simple QA models.