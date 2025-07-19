---
layout: publication
title: 'Incremental Comprehension Of Garden-path Sentences By Large Language Models:
  Semantic Interpretation, Syntactic Re-analysis, And Attention'
authors: Li et al.
conference: Cognition
year: 2024
bibkey: li2024incremental
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.16042'}]
tags: [Attention Mechanism, GPT, ASRU, CVPR, BERT, Model Architecture]
---
When reading temporarily ambiguous garden-path sentences, misinterpretations
sometimes linger past the point of disambiguation. This phenomenon has
traditionally been studied in psycholinguistic experiments using online
measures such as reading times and offline measures such as comprehension
questions. Here, we investigate the processing of garden-path sentences and the
fate of lingering misinterpretations using four large language models (LLMs):
GPT-2, LLaMA-2, Flan-T5, and RoBERTa. The overall goal is to evaluate whether
humans and LLMs are aligned in their processing of garden-path sentences and in
the lingering misinterpretations past the point of disambiguation, especially
when extra-syntactic information (e.g., a comma delimiting a clause boundary)
is present to guide processing. We address this goal using 24 garden-path
sentences that have optional transitive and reflexive verbs leading to
temporary ambiguities. For each sentence, there are a pair of comprehension
questions corresponding to the misinterpretation and the correct
interpretation. In three experiments, we (1) measure the dynamic semantic
interpretations of LLMs using the question-answering task; (2) track whether
these models shift their implicit parse tree at the point of disambiguation (or
by the end of the sentence); and (3) visualize the model components that attend
to disambiguating information when processing the question probes. These
experiments show promising alignment between humans and LLMs in the processing
of garden-path sentences, especially when extra-syntactic information is
available to guide processing.