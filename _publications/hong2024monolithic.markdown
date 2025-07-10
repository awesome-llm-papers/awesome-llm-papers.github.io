---
layout: publication
title: 'ORPO: Monolithic Preference Optimization Without Reference Model'
authors: Jiwoo Hong, Noah Lee, James Thorne
conference: Proceedings of the 2024 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
citations: 22
bibkey: hong2024monolithic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.07691'}]
tags: [Efficiency and Optimization, Training Techniques, Fine-Tuning]
---
While recent preference alignment algorithms for language models have
demonstrated promising results, supervised fine-tuning (SFT) remains imperative
for achieving successful convergence. In this paper, we study the crucial role
of SFT within the context of preference alignment, emphasizing that a minor
penalty for the disfavored generation style is sufficient for
preference-aligned SFT. Building on this foundation, we introduce a
straightforward and innovative reference model-free monolithic odds ratio
preference optimization algorithm, ORPO, eliminating the necessity for an
additional preference alignment phase. We demonstrate, both empirically and
theoretically, that the odds ratio is a sensible choice for contrasting favored
and disfavored styles during SFT across the diverse sizes from 125M to 7B.
Specifically, fine-tuning Phi-2 (2.7B), Llama-2 (7B), and Mistral (7B) with
ORPO on the UltraFeedback alone surpasses the performance of state-of-the-art
language models with more than 7B and 13B parameters: achieving up to 12.20% on
\\(\text\{AlpacaEval\}_\{2.0\}\\) (Figure 1), 66.19% on IFEval (instruction-level
loose, Table 6), and 7.32 in MT-Bench (Figure 12). We release code and model
checkpoints for Mistral-ORPO-\\(\alpha\\) (7B) and Mistral-ORPO-\\(\beta\\) (7B).