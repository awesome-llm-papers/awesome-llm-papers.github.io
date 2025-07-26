---
layout: publication
title: 'Promptcast: A New Prompt-based Learning Paradigm For Time Series Forecasting'
authors: Hao Xue, Flora D. Salim
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2023
bibkey: xue2022promptcast
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.08964'}]
tags: ["Prompting", "Time Series"]
short_authors: Hao Xue, Flora D. Salim
---
This paper presents a new perspective on time series forecasting. In existing
time series forecasting methods, the models take a sequence of numerical values
as input and yield numerical values as output. The existing SOTA models are
largely based on the Transformer architecture, modified with multiple encoding
mechanisms to incorporate the context and semantics around the historical data.
Inspired by the successes of pre-trained language foundation models, we pose a
question about whether these models can also be adapted to solve time-series
forecasting. Thus, we propose a new forecasting paradigm: prompt-based time
series forecasting (PromptCast). In this novel task, the numerical input and
output are transformed into prompts and the forecasting task is framed in a
sentence-to-sentence manner, making it possible to directly apply language
models for forecasting purposes. To support and facilitate the research of this
task, we also present a large-scale dataset (PISA) that includes three
real-world forecasting scenarios. We evaluate different SOTA numerical-based
forecasting methods and language generation models. The benchmark results with
various forecasting settings demonstrate the proposed PromptCast with language
generation models is a promising research direction. Additionally, in
comparison to conventional numerical-based forecasting, PromptCast shows a much
better generalization ability under the zero-shot setting.