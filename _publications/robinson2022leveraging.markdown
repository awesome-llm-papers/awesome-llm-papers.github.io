---
layout: publication
title: Leveraging Large Language Models For Multiple Choice Question Answering
authors: Joshua Robinson, Christopher Michael Rytting, David Wingate
conference: Arxiv
year: 2022
citations: 34
bibkey: robinson2022leveraging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.12353'}]
tags: [GPT, RAG, Few-Shot, Prompting, Model Architecture, Tokenization]
---
While large language models (LLMs) like GPT-3 have achieved impressive
results on multiple choice question answering (MCQA) tasks in the zero, one,
and few-shot settings, they generally lag behind the MCQA state of the art
(SOTA). MCQA tasks have traditionally been presented to LLMs like cloze tasks.
An LLM is conditioned on a question (without the associated answer options) and
its chosen option is the one assigned the highest probability after
normalization (for length, etc.). A more natural prompting approach is to
present the question and answer options to the LLM jointly and have it output
the symbol (e.g., "A") associated with its chosen answer option. This approach
allows the model to explicitly compare answer options, reduces computational
costs, and mitigates the effects of tokenization scheme and answer option
representations on answer selection. For the natural approach to be effective,
the LLM it is used with must be able to associate answer options with the
symbols that represent them. The LLM needs what we term multiple choice symbol
binding (MCSB) ability. This ability varies greatly by model. We show that a
model with high MCSB ability performs much better with the natural approach
than with the traditional approach across 20 diverse datasets and largely
closes the gap with the SOTA, suggesting that the MCQA ability of LLMs has been
previously underestimated.