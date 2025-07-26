---
layout: publication
title: 'Cramming 1568 Tokens Into A Single Vector And Back Again: Exploring The Limits
  Of Embedding Space Capacity'
authors: Yuri Kuratov, Mikhail Arkhipov, Aydar Bulatov, Mikhail Burtsev
conference: No Venue
year: 2025
bibkey: kuratov2025cramming
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67b5a78a6f72266cb765e779'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.13063'}]
tags: ["Efficiency", "Memory & Context"]
short_authors: Kuratov et al.
---
A range of recent works addresses the problem of compression of sequence of tokens into a shorter sequence of real-valued vectors to be used as inputs instead of token embeddings or key-value cache. These approaches allow to reduce the amount of compute in existing language models. Despite relying on powerful models as encoders, the maximum attainable lossless compression ratio is typically not higher than x10. This fact is highly intriguing because, in theory, the maximum information capacity of large real-valued vectors is far beyond the presented rates even for 16-bit precision and a modest vector size. In this work, we explore the limits of compression by replacing the encoder with a per-sample optimization procedure. We show that vectors with compression ratios up to x1500 exist, which highlights two orders of magnitude gap between existing and practically attainable solutions. Furthermore, we empirically show that the compression limits are determined not by the length of the input but by the amount of uncertainty to be reduced, namely, the cross-entropy loss on this sequence without any conditioning. The obtained limits highlight the substantial gap between the theoretical capacity of input embeddings and their practical utilization, suggesting significant room for optimization in model design.

https://huggingface.co/discussions/paper/67b5a78a6f72266cb765e779