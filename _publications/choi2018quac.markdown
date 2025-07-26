---
layout: publication
title: 'Quac : Question Answering In Context'
authors: Eunsol Choi, He He, Mohit Iyyer, Mark Yatskar, Wen-tau Yih, Yejin Choi, Percy
  Liang, Luke Zettlemoyer
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: choi2018quac
citations: 686
additional_links: [{name: Code, url: 'http://quac.ai'}, {name: Paper, url: 'https://arxiv.org/abs/1808.07036'}]
tags: ["EMNLP"]
short_authors: Choi et al.
---
We present QuAC, a dataset for Question Answering in Context that contains
14K information-seeking QA dialogs (100K questions in total). The dialogs
involve two crowd workers: (1) a student who poses a sequence of freeform
questions to learn as much as possible about a hidden Wikipedia text, and (2) a
teacher who answers the questions by providing short excerpts from the text.
QuAC introduces challenges not found in existing machine comprehension
datasets: its questions are often more open-ended, unanswerable, or only
meaningful within the dialog context, as we show in a detailed qualitative
evaluation. We also report results for a number of reference models, including
a recently state-of-the-art reading comprehension architecture extended to
model dialog context. Our best model underperforms humans by 20 F1, suggesting
that there is significant room for future work on this data. Dataset, baseline,
and leaderboard available at http://quac.ai.