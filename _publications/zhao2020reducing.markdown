---
layout: publication
title: Reducing Quantity Hallucinations In Abstractive Summarization
authors: Zheng Zhao, Shay B. Cohen, Bonnie Webber
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: zhao2020reducing
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.13312'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Zheng Zhao, Shay B. Cohen, Bonnie Webber
---
It is well-known that abstractive summaries are subject to
hallucination---including material that is not supported by the original text.
While summaries can be made hallucination-free by limiting them to general
phrases, such summaries would fail to be very informative. Alternatively, one
can try to avoid hallucinations by verifying that any specific entities in the
summary appear in the original text in a similar context. This is the approach
taken by our system, Herman. The system learns to recognize and verify quantity
entities (dates, numbers, sums of money, etc.) in a beam-worth of abstractive
summaries produced by state-of-the-art models, in order to up-rank those
summaries whose quantity terms are supported by the original text. Experimental
results demonstrate that the ROUGE scores of such up-ranked summaries have a
higher Precision than summaries that have not been up-ranked, without a
comparable loss in Recall, resulting in higher F\\(_1\\). Preliminary human
evaluation of up-ranked vs. original summaries shows people's preference for
the former.