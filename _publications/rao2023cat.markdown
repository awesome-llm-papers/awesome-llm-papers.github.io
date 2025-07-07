---
layout: publication
title: 'CAT-LM: Training Language Models On Aligned Code And Tests'
authors: Nikitha Rao, Kush Jain, Uri Alon, Claire Le Goues, Vincent J. Hellendoorn
conference: Arxiv
year: 2023
citations: 16
bibkey: rao2023cat
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01602'}]
tags: [Training Techniques, GPT, RAG, Tools, Applications, Model Architecture]
---
Testing is an integral part of the software development process. Yet, writing
tests is time-consuming and therefore often neglected. Classical test
generation tools such as EvoSuite generate behavioral test suites by optimizing
for coverage, but tend to produce tests that are hard to understand. Language
models trained on code can generate code that is highly similar to that written
by humans, but current models are trained to generate each file separately, as
is standard practice in natural language processing, and thus fail to consider
the code-under-test context when producing a test file. In this work, we
propose the Aligned Code And Tests Language Model (CAT-LM), a GPT-style
language model with 2.7 Billion parameters, trained on a corpus of Python and
Java projects. We utilize a novel pretraining signal that explicitly considers
the mapping between code and test files when available. We also drastically
increase the maximum sequence length of inputs to 8,192 tokens, 4x more than
typical code generation models, to ensure that the code context is available to
the model when generating test code. We analyze its usefulness for realistic
applications, showing that sampling with filtering (e.g., by compilability,
coverage) allows it to efficiently produce tests that achieve coverage similar
to ones written by developers while resembling their writing style. By
utilizing the code context, CAT-LM generates more valid tests than even much
larger language models trained with more data (CodeGen 16B and StarCoder) and
substantially outperforms a recent test-specific model (TeCo) at test
completion. Overall, our work highlights the importance of incorporating
software-specific insights when training language models for code and paves the
way to more powerful automated test generation.