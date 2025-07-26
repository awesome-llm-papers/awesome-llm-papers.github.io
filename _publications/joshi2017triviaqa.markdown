---
layout: publication
title: 'Triviaqa: A Large Scale Distantly Supervised Challenge Dataset For Reading
  Comprehension'
authors: Mandar Joshi, Eunsol Choi, Daniel S. Weld, Luke Zettlemoyer
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: joshi2017triviaqa
citations: 1377
additional_links: [{name: Code, url: 'http://nlp.cs.washington.edu/triviaqa/'}, {
    name: Paper, url: 'https://arxiv.org/abs/1705.03551'}]
tags: ["Datasets"]
short_authors: Joshi et al.
---
We present TriviaQA, a challenging reading comprehension dataset containing
over 650K question-answer-evidence triples. TriviaQA includes 95K
question-answer pairs authored by trivia enthusiasts and independently gathered
evidence documents, six per question on average, that provide high quality
distant supervision for answering the questions. We show that, in comparison to
other recently introduced large-scale datasets, TriviaQA (1) has relatively
complex, compositional questions, (2) has considerable syntactic and lexical
variability between questions and corresponding answer-evidence sentences, and
(3) requires more cross sentence reasoning to find answers. We also present two
baseline algorithms: a feature-based classifier and a state-of-the-art neural
network, that performs well on SQuAD reading comprehension. Neither approach
comes close to human performance (23% and 40% vs. 80%), suggesting that
TriviaQA is a challenging testbed that is worth significant future study. Data
and code available at -- http://nlp.cs.washington.edu/triviaqa/