---
layout: publication
title: 'Autoprompt: Eliciting Knowledge From Language Models With Automatically Generated
  Prompts'
authors: Taylor Shin, Yasaman Razeghi, Robert L. Logan, Eric Wallace, Sameer Singh
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: shin2020autoprompt
citations: 922
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.15980'}]
tags: ["EMNLP"]
short_authors: Shin et al.
---
The remarkable success of pretrained language models has motivated the study
of what kinds of knowledge these models learn during pretraining. Reformulating
tasks as fill-in-the-blanks problems (e.g., cloze tests) is a natural approach
for gauging such knowledge, however, its usage is limited by the manual effort
and guesswork required to write suitable prompts. To address this, we develop
AutoPrompt, an automated method to create prompts for a diverse set of tasks,
based on a gradient-guided search. Using AutoPrompt, we show that masked
language models (MLMs) have an inherent capability to perform sentiment
analysis and natural language inference without additional parameters or
finetuning, sometimes achieving performance on par with recent state-of-the-art
supervised models. We also show that our prompts elicit more accurate factual
knowledge from MLMs than the manually created prompts on the LAMA benchmark,
and that MLMs can be used as relation extractors more effectively than
supervised relation extraction models. These results demonstrate that
automatically generated prompts are a viable parameter-free alternative to
existing probing methods, and as pretrained LMs become more sophisticated and
capable, potentially a replacement for finetuning.