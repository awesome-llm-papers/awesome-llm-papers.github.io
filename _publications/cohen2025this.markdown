---
layout: publication
title: 'This Time Is Different: An Observability Perspective On Time Series Foundation
  Models'
authors: "Ben Cohen, Emaad Khwaja, Youssef Doubli, Salahidine Lemaachi, Chris Lettieri,\
  \ Charles Masson, Hugo Miccinilli, Elise Ram\xE9, Qiqi Ren, Afshin Rostamizadeh,\
  \ Jean Ogier Du Terrail, Anna-monica Toon, Kan Wang, Stephan Xie, David Asker, Ameet\
  \ Talwalkar, Othmane Abou-amal"
conference: No Venue
year: 2025
bibkey: cohen2025this
additional_links: [{name: Code, url: 'https://huggingface.co/Datadog/Toto-Open-Base-1.0'},
  {name: Code, url: 'https://github.com/DataDog/toto'}, {name: Code, url: 'https://huggingface.co/discussions/paper/682f037627c6b9d4500dedd6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.14766'}]
tags: ["Time Series"]
short_authors: Cohen et al.
---
We introduce Toto, a time series forecasting foundation model with 151 million parameters. Toto uses a modern decoder-only architecture coupled with architectural innovations designed to account for specific challenges found in multivariate observability time series data. Toto's pre-training corpus is a mixture of observability data, open datasets, and synthetic data, and is 4-10times larger than those of leading time series foundation models. Additionally, we introduce BOOM, a large-scale benchmark consisting of 350 million observations across 2,807 real-world time series. For both Toto and BOOM, we source observability data exclusively from Datadog's own telemetry and internal observability metrics. Extensive evaluations demonstrate that Toto achieves state-of-the-art performance on both BOOM and on established general purpose time series forecasting benchmarks. Toto's model weights, inference code, and evaluation scripts, as well as BOOM's data and evaluation code, are all available as open source under the Apache 2.0 License available at https://huggingface.co/Datadog/Toto-Open-Base-1.0 and https://github.com/DataDog/toto.

https://huggingface.co/discussions/paper/682f037627c6b9d4500dedd6