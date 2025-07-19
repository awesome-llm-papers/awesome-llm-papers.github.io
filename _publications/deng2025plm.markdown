---
layout: publication
title: 'PLM: Efficient Peripheral Language Models Hardware-co-designed For Ubiquitous
  Computing'
authors: Deng et al.
conference: IEEE Pervasive Computing
year: 2025
bibkey: deng2025plm
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.12167'}]
tags: [Scaling Laws, RAG, Training Techniques, Attention Mechanism, Agentic, Evaluation,
  Transformer, Model Architecture, Efficiency And Optimization, Reinforcement Learning,
  Applications, Fine Tuning, Large Scale Training, Datasets]
---
While scaling laws have been continuously validated in large language models
(LLMs) with increasing model parameters, the inherent tension between the
inference demands of LLMs and the limited resources of edge devices poses a
critical challenge to the development of edge intelligence. Recently, numerous
small language models have emerged, aiming to distill the capabilities of LLMs
into smaller footprints. However, these models often retain the fundamental
architectural principles of their larger counterparts, still imposing
considerable strain on the storage and bandwidth capacities of edge devices. In
this paper, we introduce the PLM, a Peripheral Language Model, developed
through a co-design process that jointly optimizes model architecture and edge
system constraints. The PLM utilizes a Multi-head Latent Attention mechanism
and employs the squared ReLU activation function to encourage sparsity, thereby
reducing peak memory footprint during inference. During training, we collect
and reorganize open-source datasets, implement a multi-phase training strategy,
and empirically investigate the Warmup-Stable-Decay-Constant (WSDC) learning
rate scheduler. Additionally, we incorporate Reinforcement Learning from Human
Feedback (RLHF) by adopting the ARIES preference learning approach. Following a
two-phase SFT process, this method yields performance gains of 2% in general
tasks, 9% in the GSM8K task, and 11% in coding tasks. In addition to its novel
architecture, evaluation results demonstrate that PLM outperforms existing
small language models trained on publicly available data while maintaining the
lowest number of activated parameters. Furthermore, deployment across various
edge devices, including consumer-grade GPUs, mobile phones, and Raspberry Pis,
validates PLM's suitability for peripheral applications. The PLM series models
are publicly available at https://github.com/plm-team/PLM.