---
layout: publication
title: Financial Statement Analysis With Large Language Models
authors: Alex Kim, Maximilian Muhn, Valeri Nikolaev
conference: Arxiv
year: 2024
citations: 15
bibkey: kim2024financial
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.17866'}]
tags: [Training Techniques, Model Architecture, GPT]
---
We investigate whether large language models (LLMs) can successfully perform
financial statement analysis in a way similar to a professional human analyst.
We provide standardized and anonymous financial statements to GPT4 and instruct
the model to analyze them to determine the direction of firms' future earnings.
Even without narrative or industry-specific information, the LLM outperforms
financial analysts in its ability to predict earnings changes directionally.
The LLM exhibits a relative advantage over human analysts in situations when
the analysts tend to struggle. Furthermore, we find that the prediction
accuracy of the LLM is on par with a narrowly trained state-of-the-art ML
model. LLM prediction does not stem from its training memory. Instead, we find
that the LLM generates useful narrative insights about a company's future
performance. Lastly, our trading strategies based on GPT's predictions yield a
higher Sharpe ratio and alphas than strategies based on other models. Our
results suggest that LLMs may take a central role in analysis and
decision-making.