---
layout: publication
title: 'Spectra: A Comprehensive Study Of Ternary, Quantized, And FP16 Language Models'
authors: Ayush Kaushal, Tejas Pandey, Tejas Vaidhya, Aaryan Bhagat, Irina Rish
conference: No Venue
year: 2024
bibkey: kaushal2024spectra
additional_links: [{name: Code, url: 'https://github.com/NolanoOrg/SpectraSuite\{https://github.com/NolanoOrg/SpectraSuite\'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.12327'}]
tags: ["Model Architecture"]
short_authors: Kaushal et al.
---
Post-training quantization is the leading method for addressing memory-related bottlenecks in LLM inference, but unfortunately, it suffers from significant performance degradation below 4-bit precision. An alternative approach involves training compressed models directly at a low bitwidth (e.g., binary or ternary models). However, the performance, training dynamics, and scaling trends of such models are not yet well understood. To address this issue, we train and openly release the Spectra LLM suite consisting of 54 language models ranging from 99M to 3.9B parameters, trained on 300B tokens. Spectra includes FloatLMs, post-training quantized QuantLMs (3, 4, 6, and 8 bits), and ternary LLMs (TriLMs) - our improved architecture for ternary language modeling, which significantly outperforms previously proposed ternary models of a given size (in bits), matching half-precision models at scale. For example, TriLM 3.9B is (bit-wise) smaller than the half-precision FloatLM 830M, but matches half-precision FloatLM 3.9B in commonsense reasoning and knowledge benchmarks. However, TriLM 3.9B is also as toxic and stereotyping as FloatLM 3.9B, a model six times larger in size. Additionally, TriLM 3.9B lags behind FloatLM in perplexity on validation splits and web-based corpora but performs better on less noisy datasets like Lambada and PennTreeBank. To enhance understanding of low-bitwidth models, we are releasing 500+ intermediate checkpoints of the Spectra suite at https://github.com/NolanoOrg/SpectraSuite\{https://github.com/NolanoOrg/SpectraSuite\}.

https://huggingface.co/discussions/paper/669883b563880317128f2340