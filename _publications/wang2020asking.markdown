---
layout: publication
title: Asking And Answering Questions To Evaluate The Factual Consistency Of Summaries
authors: Alex Wang, Kyunghyun Cho, Mike Lewis
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: wang2020asking
citations: 290
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.04228'}]
tags: ["Evaluation"]
short_authors: Alex Wang, Kyunghyun Cho, Mike Lewis
---
Practical applications of abstractive summarization models are limited by
frequent factual inconsistencies with respect to their input. Existing
automatic evaluation metrics for summarization are largely insensitive to such
errors. We propose an automatic evaluation protocol called QAGS (pronounced
"kags") that is designed to identify factual inconsistencies in a generated
summary. QAGS is based on the intuition that if we ask questions about a
summary and its source, we will receive similar answers if the summary is
factually consistent with the source. To evaluate QAGS, we collect human
judgments of factual consistency on model-generated summaries for the
CNN/DailyMail (Hermann et al., 2015) and XSUM (Narayan et al., 2018)
summarization datasets. QAGS has substantially higher correlations with these
judgments than other automatic evaluation metrics. Also, QAGS offers a natural
form of interpretability: The answers and questions generated while computing
QAGS indicate which tokens of a summary are inconsistent and why. We believe
QAGS is a promising tool in automatically generating usable and factually
consistent text.