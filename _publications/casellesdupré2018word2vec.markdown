---
layout: publication
title: 'Word2vec Applied To Recommendation: Hyperparameters Matter'
authors: "Caselles-dupr\xE9 Hugo, Lesaint Florian, Royo-letelier Jimena"
conference: Proceedings of the 12th ACM Conference on Recommender Systems
year: 2018
bibkey: "casellesdupr\xE92018word2vec"
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.04212'}]
tags: [Datasets, RecSys, Applications]
---
Skip-gram with negative sampling, a popular variant of Word2vec originally
designed and tuned to create word embeddings for Natural Language Processing,
has been used to create item embeddings with successful applications in
recommendation. While these fields do not share the same type of data, neither
evaluate on the same tasks, recommendation applications tend to use the same
already tuned hyperparameters values, even if optimal hyperparameters values
are often known to be data and task dependent. We thus investigate the marginal
importance of each hyperparameter in a recommendation setting through large
hyperparameter grid searches on various datasets. Results reveal that
optimizing neglected hyperparameters, namely negative sampling distribution,
number of epochs, subsampling parameter and window-size, significantly improves
performance on a recommendation task, and can increase it by an order of
magnitude. Importantly, we find that optimal hyperparameters configurations for
Natural Language Processing tasks and Recommendation tasks are noticeably
different.