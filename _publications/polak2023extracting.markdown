---
layout: publication
title: Extracting Accurate Materials Data From Research Papers With Conversational
  Language Models And Prompt Engineering
authors: Maciej P. Polak, Dane Morgan
conference: Nature Communications
year: 2024
bibkey: polak2023extracting
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.05352'}]
tags: ["Tools"]
short_authors: Maciej P. Polak, Dane Morgan
---
There has been a growing effort to replace manual extraction of data from
research papers with automated data extraction based on natural language
processing, language models, and recently, large language models (LLMs).
Although these methods enable efficient extraction of data from large sets of
research papers, they require a significant amount of up-front effort,
expertise, and coding. In this work we propose the ChatExtract method that can
fully automate very accurate data extraction with minimal initial effort and
background, using an advanced conversational LLM. ChatExtract consists of a set
of engineered prompts applied to a conversational LLM that both identify
sentences with data, extract that data, and assure the data's correctness
through a series of follow-up questions. These follow-up questions largely
overcome known issues with LLMs providing factually inaccurate responses.
ChatExtract can be applied with any conversational LLMs and yields very high
quality data extraction. In tests on materials data we find precision and
recall both close to 90% from the best conversational LLMs, like ChatGPT-4. We
demonstrate that the exceptional performance is enabled by the information
retention in a conversational model combined with purposeful redundancy and
introducing uncertainty through follow-up prompts. These results suggest that
approaches similar to ChatExtract, due to their simplicity, transferability,
and accuracy are likely to become powerful tools for data extraction in the
near future. Finally, databases for critical cooling rates of metallic glasses
and yield strengths of high entropy alloys are developed using ChatExtract.