---
layout: publication
title: Log-linear Combinations Of Monolingual And Bilingual Neural Machine Translation
  Models For Automatic Post-editing
authors: Marcin Junczys-dowmunt, Roman Grundkiewicz
conference: 'Proceedings of the First Conference on Machine Translation: Volume 2,
  Shared Task Papers'
year: 2016
bibkey: junczysdowmunt2016log
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.04800'}]
tags: ["Training Techniques"]
short_authors: Marcin Junczys-dowmunt, Roman Grundkiewicz
---
This paper describes the submission of the AMU (Adam Mickiewicz University)
team to the Automatic Post-Editing (APE) task of WMT 2016. We explore the
application of neural translation models to the APE problem and achieve good
results by treating different models as components in a log-linear model,
allowing for multiple inputs (the MT-output and the source) that are decoded to
the same target language (post-edited translations). A simple string-matching
penalty integrated within the log-linear model is used to control for higher
faithfulness with regard to the raw machine translation output. To overcome the
problem of too little training data, we generate large amounts of artificial
data. Our submission improves over the uncorrected baseline on the unseen test
set by -3.2% TER and +5.5% BLEU and outperforms any other system submitted to
the shared-task by a large margin.