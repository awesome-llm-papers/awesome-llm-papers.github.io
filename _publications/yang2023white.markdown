---
layout: publication
title: 'Whitefox: White-box Compiler Fuzzing Empowered By Large Language Models'
authors: Chenyuan Yang et al.
conference: Proceedings of the ACM on Programming Languages
year: 2023
citations: 19
bibkey: yang2023white
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.15991'}]
tags: [Agentic, Tools, Efficiency and Optimization, Evaluation]
---
Compiler correctness is crucial, as miscompilation can falsify program
behaviors, leading to serious consequences. Fuzzing has been studied to uncover
compiler defects. However, compiler fuzzing remains challenging: Existing arts
focus on black- and grey-box fuzzing, which generates tests without sufficient
understanding of internal compiler behaviors. Meanwhile, traditional white-box
techniques, like symbolic execution, are computationally inapplicable to the
giant codebase of compilers. Recent advances demonstrate that Large Language
Models (LLMs) excel in code generation/understanding tasks. Nonetheless,
guiding LLMs with compiler source-code information remains a missing piece of
research in compiler testing.
  To this end, we propose WhiteFox, the first white-box compiler fuzzer using
LLMs with source-code information to test compiler optimization, with a
spotlight on detecting deep logic bugs in the deep learning (DL) compilers.
WhiteFox adopts a multi-agent framework: an LLM-based analysis agent examines
the low-level optimization source code and produces requirements on the
high-level test programs that can trigger the optimization; an LLM-based
generation agent produces test programs based on the summarized requirements.
Additionally, optimization-triggering tests are used as feedback to enhance the
generation on the fly. Our evaluation on the three most popular DL compilers
(i.e., PyTorch Inductor, TensorFlow-XLA, and TensorFlow Lite) shows WhiteFox
can generate high-quality test programs to exercise deep optimizations,
practicing up to 8X more than state-of-the-art fuzzers. WhiteFox has found 101
bugs for the DL compilers, with 92 confirmed as previously unknown and 70
fixed. WhiteFox has been acknowledged by the PyTorch team and is being
incorporated into its development workflow. Beyond DL compilers, WhiteFox can
also be adapted for compilers in different domains.