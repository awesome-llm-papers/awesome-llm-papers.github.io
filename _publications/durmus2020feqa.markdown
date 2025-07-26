---
layout: publication
title: 'FEQA: A Question Answering Evaluation Framework For Faithfulness Assessment
  In Abstractive Summarization'
authors: Esin Durmus, He He, Mona Diab
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: durmus2020feqa
citations: 277
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.03754'}]
tags: ["Evaluation"]
short_authors: Esin Durmus, He He, Mona Diab
---
Neural abstractive summarization models are prone to generate content
inconsistent with the source document, i.e. unfaithful. Existing automatic
metrics do not capture such mistakes effectively. We tackle the problem of
evaluating faithfulness of a generated summary given its source document. We
first collected human annotations of faithfulness for outputs from numerous
models on two datasets. We find that current models exhibit a trade-off between
abstractiveness and faithfulness: outputs with less word overlap with the
source document are more likely to be unfaithful. Next, we propose an automatic
question answering (QA) based metric for faithfulness, FEQA, which leverages
recent advances in reading comprehension. Given question-answer pairs generated
from the summary, a QA model extracts answers from the document; non-matched
answers indicate unfaithful information in the summary. Among metrics based on
word overlap, embedding similarity, and learned language understanding models,
our QA-based metric has significantly higher correlation with human
faithfulness scores, especially on highly abstractive summaries.