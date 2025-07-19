---
layout: publication
title: 'Inpars Toolkit: A Unified And Reproducible Synthetic Data Generation Pipeline
  For Neural Information Retrieval'
authors: Abonizio et al.
conference: Proceedings of the 45th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2023
bibkey: abonizio2023inpars
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.04601'}]
tags: [Training Techniques, Prompting, Evaluation, Reinforcement Learning, SIGIR,
  Datasets]
---
Recent work has explored Large Language Models (LLMs) to overcome the lack of
training data for Information Retrieval (IR) tasks. The generalization
abilities of these models have enabled the creation of synthetic in-domain data
by providing instructions and a few examples on a prompt. InPars and
Promptagator have pioneered this approach and both methods have demonstrated
the potential of using LLMs as synthetic data generators for IR tasks. This
makes them an attractive solution for IR tasks that suffer from a lack of
annotated data. However, the reproducibility of these methods was limited,
because InPars' training scripts are based on TPUs -- which are not widely
accessible -- and because the code for Promptagator was not released and its
proprietary LLM is not publicly accessible. To fully realize the potential of
these methods and make their impact more widespread in the research community,
the resources need to be accessible and easy to reproduce by researchers and
practitioners. Our main contribution is a unified toolkit for end-to-end
reproducible synthetic data generation research, which includes generation,
filtering, training and evaluation. Additionally, we provide an interface to IR
libraries widely used by the community and support for GPU. Our toolkit not
only reproduces the InPars method and partially reproduces Promptagator, but
also provides a plug-and-play functionality allowing the use of different LLMs,
exploring filtering methods and finetuning various reranker models on the
generated data. We also made available all the synthetic data generated in this
work for the 18 different datasets in the BEIR benchmark which took more than
2,000 GPU hours to be generated as well as the reranker models finetuned on the
synthetic data. Code and data are available at
https://github.com/zetaalphavector/InPars