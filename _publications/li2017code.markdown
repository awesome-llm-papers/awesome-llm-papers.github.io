---
layout: publication
title: Code Completion With Neural Attention And Pointer Networks
authors: Jian Li, Yue Wang, Michael R. Lyu, Irwin King
conference: Proceedings of the Twenty-Seventh International Joint Conference on Artificial
  Intelligence
year: 2018
bibkey: li2017code
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.09573'}]
tags: ["IJCAI", "Llm For Code", "Model Architecture"]
short_authors: Li et al.
---
Intelligent code completion has become an essential research task to
accelerate modern software development. To facilitate effective code completion
for dynamically-typed programming languages, we apply neural language models by
learning from large codebases, and develop a tailored attention mechanism for
code completion. However, standard neural language models even with attention
mechanism cannot correctly predict the out-of-vocabulary (OoV) words that
restrict the code completion performance. In this paper, inspired by the
prevalence of locally repeated terms in program source code, and the recently
proposed pointer copy mechanism, we propose a pointer mixture network for
better predicting OoV words in code completion. Based on the context, the
pointer mixture network learns to either generate a within-vocabulary word
through an RNN component, or regenerate an OoV word from local context through
a pointer component. Experiments on two benchmarked datasets demonstrate the
effectiveness of our attention mechanism and pointer mixture network on the
code completion task.