---
layout: publication
title: 'Pairreranker: Pairwise Reranking For Natural Language Generation'
authors: Jiang Dongfu, Lin Bill Yuchen, Ren Xiang
conference: Computational Linguistics
year: 2022
bibkey: jiang2022pairreranker
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.10555'}]
tags: [Model Architecture, TACL, ACL, GPT, NAACL, EACL, COLING]
---
Pre-trained language models have been successful in natural language
generation (NLG) tasks. While various decoding methods have been employed, they
often produce suboptimal results. We first present an empirical analysis of
three NLG tasks: summarization, machine translation, and constrained text
generation. We found that selecting the best output from the results of
multiple decoding methods can significantly improve performance. To further
improve reranking for NLG tasks, we proposed a novel method,
\textsc\{PairReranker\}, which uses a single encoder and a pairwise loss function
to jointly encode a source input and a pair of candidates and compare them.
Experiments on three NLG tasks demonstrated the effectiveness and flexibility
of \textsc\{PairReranker\}, showing strong results, compared with previous
baselines. In addition, our \textsc\{PairReranker\} can generalize to
significantly improve GPT-3 (text-davinci-003) results (e.g., 24.55% on
CommonGen and 11.35% on WMT18 zh-en), even though our rerankers are not
trained with any GPT-3 candidates.