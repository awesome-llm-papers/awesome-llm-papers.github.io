---
layout: publication
title: Large Language Models Effectively Leverage Document-level Context For Literary
  Translation, But Critical Errors Persist
authors: Marzena Karpinska, Mohit Iyyer
conference: Arxiv
year: 2023
citations: 16
bibkey: karpinska2023large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.03245'}]
tags: [RAG, GPT, Model Architecture]
---
Large language models (LLMs) are competitive with the state of the art on a
wide range of sentence-level translation datasets. However, their ability to
translate paragraphs and documents remains unexplored because evaluation in
these settings is costly and difficult. We show through a rigorous human
evaluation that asking the Gpt-3.5 (text-davinci-003) LLM to translate an
entire literary paragraph (e.g., from a novel) at once results in
higher-quality translations than standard sentence-by-sentence translation
across 18 linguistically-diverse language pairs (e.g., translating into and out
of Japanese, Polish, and English). Our evaluation, which took approximately 350
hours of effort for annotation and analysis, is conducted by hiring translators
fluent in both the source and target language and asking them to provide both
span-level error annotations as well as preference judgments of which system's
translations are better. We observe that discourse-level LLM translators commit
fewer mistranslations, grammar errors, and stylistic inconsistencies than
sentence-level approaches. With that said, critical errors still abound,
including occasional content omissions, and a human translator's intervention
remains necessary to ensure that the author's voice remains intact. We publicly
release our dataset and error annotations to spur future research on evaluation
of document-level literary translation.