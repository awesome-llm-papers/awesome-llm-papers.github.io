---
layout: publication
title: 'OPT: Open Pre-trained Transformer Language Models'
authors: [susan Zhang, stephen Roller, naman Goyal, mikel Artetxe, moya Chen, shuohui
    Chen, christopher Dewan, mona Diab, xian Li, xi Victoria Lin, todor Mihaylov,
  myle Ott, sam Shleifer, kurt Shuster, daniel Simig, punit Singh Koura, anjali Sridhar,
  tianlu Wang, luke Zettlemoyer]
conference: Arxiv
year: 2022
bibkey: susan2022opt
citations: 820
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2205.01068v4'}]
tags: ["Few-Shot", "Model Architecture"]
short_authors: Zhang et al.
---
Large language models, which are often trained for hundreds of thousands of
compute days, have shown remarkable capabilities for zero- and few-shot
learning. Given their computational cost, these models are difficult to
replicate without significant capital. For the few that are available through
APIs, no access is granted to the full model weights, making them difficult to
study. We present Open Pre-trained Transformers (OPT), a suite of decoder-only
pre-trained transformers ranging from 125M to 175B parameters, which we aim to
fully and responsibly share with interested researchers. We show that OPT-175B
is comparable to GPT-3, while requiring only 1/7th the carbon footprint to
develop. We are also releasing our logbook detailing the infrastructure
challenges we faced, along with code for experimenting with all of the released
models.