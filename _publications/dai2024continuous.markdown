---
layout: publication
title: Continuous Risk Prediction
authors: Dai Yi
conference: Nature Protocols
year: 2024
bibkey: dai2024continuous
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.09449'}]
tags: [RAG, Prompting, Tools, Model Architecture, Reinforcement Learning, Applications]
---
Lifelong learning (LL) capabilities are essential for QA models to excel in
real-world applications, and architecture-based LL approaches have proven to be
a promising direction for achieving this goal. However, adapting existing
methods to QA tasks is far from straightforward. Many prior approaches either
rely on access to task identities during testing or fail to adequately model
samples from unseen tasks, which limits their practical applicability. To
overcome these limitations, we introduce Diana , a novel
\underline\{d\}ynam\underline\{i\}c \underline\{a\}rchitecture-based
lifelo\underline\{n\}g Q\underline\{A\} framework designed to learn a sequence of
QA tasks using a prompt-enhanced language model.Diana leverages four
hierarchically structured types of prompts to capture QA knowledge at multiple
levels of granularity. Task-level prompts are specifically designed to encode
task-specific knowledge, ensuring strong lifelong learning performance.
Meanwhile, instance-level prompts are utilized to capture shared knowledge
across diverse input samples, enhancing the model's generalization
capabilities. Additionally, Diana incorporates dedicated prompts to explicitly
handle unseen tasks and introduces a set of prompt key vectors that facilitate
efficient knowledge transfer and sharing between tasks. Through extensive
experimentation, we demonstrate that Diana achieves state-of-the-art
performance among lifelong QA models, with particularly notable improvements in
its ability to handle previously unseen tasks. This makes Diana a significant
advancement in the field of lifelong learning for question-answering systems.