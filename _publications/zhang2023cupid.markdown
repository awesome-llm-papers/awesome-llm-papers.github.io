---
layout: publication
title: 'CUPID: Leveraging Chatgpt For More Accurate Duplicate Bug Report Detection'
authors: Zhang et al.
conference: 2013 10th Working Conference on Mining Software Repositories (MSR)
year: 2023
bibkey: zhang2023cupid
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.10022'}]
tags: [RAG, GPT, Evaluation, Model Architecture, Datasets]
---
Duplicate bug report detection (DBRD) is a long-standing challenge in both
academia and industry. Over the past decades, researchers have proposed various
approaches to detect duplicate bug reports more accurately. With the recent
advancement of deep learning, researchers have also proposed several deep
learning-based approaches to address the DBRD task. In the bug repositories
with many bug reports, deep learning-based approaches have shown promising
performance. However, in the bug repositories with a smaller number of bug
reports, i.e., around 10k, the existing deep learning approaches show worse
performance than the traditional approaches. Traditional approaches have
limitations, too, e.g., they are usually based on the bag-of-words model, which
cannot capture the semantics of bug reports. To address these aforementioned
challenges, we seek to leverage a state-of-the-art large language model (LLM)
to improve the performance of the traditional DBRD approach.
  In this paper, we propose an approach called CUPID, which combines the
bestperforming traditional DBRD approach (i.e., REP) with the state-of-the-art
LLM (i.e., ChatGPT). We conducted an evaluation by comparing CUPID with three
existing approaches on three datasets. The experimental results show that CUPID
achieves state-of-theart results, reaching Recall Rate@10 scores ranging from
0.602 to 0.654 across all the datasets analyzed. In particular, CUPID improves
over the prior state-ofthe-art approach by 5% - 8% in terms of Recall Rate@10
in the datasets. CUPID also surpassed the state-of-the-art deep learning-based
DBRD approach by up to 82%.