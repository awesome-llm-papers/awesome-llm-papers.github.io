---
layout: publication
title: 'Large Language Models On Graphs: A Comprehensive Survey'
authors: Bowen Jin et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2023
citations: 19
bibkey: jin2023large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.02783'}, {name: Code,
    url: 'https://github.com/PeterGriffinJin/Awesome-Language-Model-on-Graphs'}]
tags: [Has Code, Model Architecture, Applications, Survey Paper, Reinforcement Learning,
  GPT, Evaluation]
---
Large language models (LLMs), such as GPT4 and LLaMA, are creating
significant advancements in natural language processing, due to their strong
text encoding/decoding ability and newly found emergent capability (e.g.,
reasoning). While LLMs are mainly designed to process pure texts, there are
many real-world scenarios where text data is associated with rich structure
information in the form of graphs (e.g., academic networks, and e-commerce
networks) or scenarios where graph data is paired with rich textual information
(e.g., molecules with descriptions). Besides, although LLMs have shown their
pure text-based reasoning ability, it is underexplored whether such ability can
be generalized to graphs (i.e., graph-based reasoning). In this paper, we
provide a systematic review of scenarios and techniques related to large
language models on graphs. We first summarize potential scenarios of adopting
LLMs on graphs into three categories, namely pure graphs, text-attributed
graphs, and text-paired graphs. We then discuss detailed techniques for
utilizing LLMs on graphs, including LLM as Predictor, LLM as Encoder, and LLM
as Aligner, and compare the advantages and disadvantages of different schools
of models. Furthermore, we discuss the real-world applications of such methods
and summarize open-source codes and benchmark datasets. Finally, we conclude
with potential future research directions in this fast-growing field. The
related source can be found at
https://github.com/PeterGriffinJin/Awesome-Language-Model-on-Graphs.