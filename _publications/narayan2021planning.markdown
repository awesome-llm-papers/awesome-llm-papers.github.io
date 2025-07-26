---
layout: publication
title: Planning With Learned Entity Prompts For Abstractive Summarization
authors: "Shashi Narayan, Yao Zhao, Joshua Maynez, Gon\xE7alo Simoes, Vitaly Nikolaev,\
  \ Ryan Mcdonald"
conference: Transactions of the Association for Computational Linguistics
year: 2021
bibkey: narayan2021planning
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.07606'}]
tags: ["Model Architecture", "Prompting", "TACL"]
short_authors: Narayan et al.
---
We introduce a simple but flexible mechanism to learn an intermediate plan to
ground the generation of abstractive summaries. Specifically, we prepend (or
prompt) target summaries with entity chains -- ordered sequences of entities
mentioned in the summary. Transformer-based sequence-to-sequence models are
then trained to generate the entity chain and then continue generating the
summary conditioned on the entity chain and the input. We experimented with
both pretraining and finetuning with this content planning objective. When
evaluated on CNN/DailyMail, XSum, SAMSum and BillSum, we demonstrate
empirically that the grounded generation with the planning objective improves
entity specificity and planning in summaries for all datasets, and achieves
state-of-the-art performance on XSum and SAMSum in terms of Rouge. Moreover, we
demonstrate empirically that planning with entity chains provides a mechanism
to control hallucinations in abstractive summaries. By prompting the decoder
with a modified content plan that drops hallucinated entities, we outperform
state-of-the-art approaches for faithfulness when evaluated automatically and
by humans.