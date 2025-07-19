---
layout: publication
title: 'Superbpe: Space Travel For Language Models'
authors: Liu et al.
conference: Computer Speech &amp; Language
year: 2025
bibkey: liu2025superbpe
citations: 217
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.13423'}]
tags: [RAG, Ethics And Bias, Transformer, Tokenization, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning]
---
The assumption across nearly all language model (LM) tokenization schemes is
that tokens should be subwords, i.e., contained within word boundaries. While
providing a seemingly reasonable inductive bias, is this common practice
limiting the potential of modern LMs? Whitespace is not a reliable delimiter of
meaning, as evidenced by multi-word expressions (e.g., "by the way"),
crosslingual variation in the number of words needed to express a concept
(e.g., "spacesuit helmet" in German is "raumanzughelm"), and languages that do
not use whitespace at all (e.g., Chinese). To explore the potential of
tokenization beyond subwords, we introduce a "superword" tokenizer, SuperBPE,
which incorporates a simple pretokenization curriculum into the byte-pair
encoding (BPE) algorithm to first learn subwords, then superwords that bridge
whitespace. This brings dramatic improvements in encoding efficiency: when
fixing the vocabulary size to 200k, SuperBPE encodes a fixed piece of text with
up to 33% fewer tokens than BPE on average. In experiments, we pretrain 8B
transformer LMs from scratch while fixing the model size, vocabulary size, and
train compute, varying *only* the algorithm for learning the vocabulary. Our
model trained with SuperBPE achieves an average +4.0% absolute improvement over
the BPE baseline across 30 downstream tasks (including +8.2% on MMLU), while
simultaneously requiring 27% less compute at inference time. In analysis, we
find that SuperBPE results in segmentations of text that are more uniform in
per-token difficulty. Qualitatively, this may be because SuperBPE tokens often
capture common multi-word expressions that function semantically as a single
unit. SuperBPE is a straightforward, local modification to tokenization that
improves both encoding efficiency and downstream performance, yielding better
language models overall.