---
layout: publication
title: 'Toto: Time Series Optimized Transformer For Observability'
authors: "Ben Cohen, Emaad Khwaja, Kan Wang, Charles Masson, Elise Ram\xE9, Youssef\
  \ Doubli, Othmane Abou-amal"
conference: No Venue
year: 2024
bibkey: cohen2024toto
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/669533d1f5481f2dcd00dd4b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.07874'}]
tags: ["Model Architecture", "Time Series", "Tools"]
short_authors: Cohen et al.
---
This technical report describes the Time Series Optimized Transformer for Observability (Toto), a new state of the art foundation model for time series forecasting developed by Datadog. In addition to advancing the state of the art on generalized time series benchmarks in domains such as electricity and weather, this model is the first general-purpose time series forecasting foundation model to be specifically tuned for observability metrics. Toto was trained on a dataset of one trillion time series data points, the largest among all currently published time series foundation models. Alongside publicly available time series datasets, 75% of the data used to train Toto consists of fully anonymous numerical metric data points from the Datadog platform. In our experiments, Toto outperforms existing time series foundation models on observability data. It does this while also excelling at general-purpose forecasting tasks, achieving state-of-the-art zero-shot performance on multiple open benchmark datasets.

https://huggingface.co/discussions/paper/669533d1f5481f2dcd00dd4b