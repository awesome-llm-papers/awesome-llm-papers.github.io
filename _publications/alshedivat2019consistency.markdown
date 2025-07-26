---
layout: publication
title: Consistency By Agreement In Zero-shot Neural Machine Translation
authors: Maruan Al-shedivat, Ankur P. Parikh
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: alshedivat2019consistency
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.02338'}]
tags: ["Training Techniques"]
short_authors: Maruan Al-shedivat, Ankur P. Parikh
---
Generalization and reliability of multilingual translation often highly
depend on the amount of available parallel data for each language pair of
interest. In this paper, we focus on zero-shot generalization---a challenging
setup that tests models on translation directions they have not been optimized
for at training time. To solve the problem, we (i) reformulate multilingual
translation as probabilistic inference, (ii) define the notion of zero-shot
consistency and show why standard training often results in models unsuitable
for zero-shot tasks, and (iii) introduce a consistent agreement-based training
method that encourages the model to produce equivalent translations of parallel
sentences in auxiliary languages. We test our multilingual NMT models on
multiple public zero-shot translation benchmarks (IWSLT17, UN corpus, Europarl)
and show that agreement-based learning often results in 2-3 BLEU zero-shot
improvement over strong baselines without any loss in performance on supervised
translation directions.