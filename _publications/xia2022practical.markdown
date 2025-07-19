---
layout: publication
title: Practical Program Repair In The Era Of Large Pre-trained Language Models
authors: Xia Chunqiu Steven, Wei Yuxiang, Zhang Lingming
conference: 2023 IEEE/ACM 45th International Conference on Software Engineering (ICSE)
year: 2022
bibkey: xia2022practical
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.14179'}]
tags: [Datasets, LLM for Code, RAG, LLM For Code]
---
Automated Program Repair (APR) aims to help developers automatically patch
software bugs. However, current state-of-the-art traditional and learning-based
APR techniques face the problem of limited patch variety, failing to fix
complicated bugs. This is mainly due to the reliance on bug-fixing datasets to
craft fix templates or directly predict potential patches. Large Pre-Trained
Language Models (PLMs), trained using billions of text/code tokens, can
potentially help avoid this issue. Very recently, researchers have directly
leveraged PLMs for APR without relying on any bug-fixing datasets. Meanwhile,
such existing work either failed to include state-of-the-art PLMs or was not
evaluated on realistic datasets.
  In this work, we perform the first extensive study on directly applying PLMs
for APR. We select 9 recent state-of-the-art PLMs, including both generative
and infilling models, ranging from 125M to 20B in size. We designed 3 different
repair settings to evaluate the different ways we can use PLMs to generate
patches. We apply the PLMs under these repair settings on 5 datasets across 3
different languages and compare different PLMs in the number of bugs fixed,
generation speed and compilation rate. Our study demonstrates that directly
applying state-of-the-art PLMs can already substantially outperform all
existing APR techniques on all our datasets. Among the studied PLMs, the
scaling effect exists for APR where larger models tend to achieve better
performance. Also, we show for the first time that suffix code after the buggy
line (adopted in infilling-style APR) is important in not only generating more
fixes but more patches with higher compilation rate. Besides patch generation,
the PLMs consider correct patches to be more natural than other ones, and can
even be leveraged for effective patch ranking or patch correctness checking.