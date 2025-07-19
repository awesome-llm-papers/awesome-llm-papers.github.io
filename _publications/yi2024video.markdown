---
layout: publication
title: 'Video-text Dataset Construction From Multi-ai Feedback: Promoting Weak-to-strong
  Preference Learning For Video Large Language Models'
authors: Yi et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: yi2024video
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.16201'}]
tags: [RAG, Training Techniques, Tools, CVPR, Ethics And Bias, Evaluation, Efficiency
    And Optimization, Reinforcement Learning, Multimodal Models, Datasets]
---
High-quality video-text preference data is crucial for Multimodal Large
Language Models (MLLMs) alignment. However, existing preference data is very
scarce. Obtaining VQA preference data for preference training is costly, and
manually annotating responses is highly unreliable, which could result in
low-quality pairs. Meanwhile, AI-generated responses controlled by temperature
adjustment lack diversity. To address these issues, we propose a high-quality
VQA preference dataset, called \textit\{\textbf\{M\}ultiple \textbf\{M\}ultimodal
\textbf\{A\}rtificial \textbf\{I\}ntelligence \textbf\{P\}reference Datasets in
\textbf\{V\}QA\} (\textbf\{MMAIP-V\}), which is constructed by sampling from the
response distribution set and using an external scoring function for response
evaluation. Furthermore, to fully leverage the preference knowledge in MMAIP-V
and ensure sufficient optimization, we propose \textit\{\textbf\{Iter\}ative
\textbf\{W\}eak-to-\textbf\{S\}trong \textbf\{R\}einforcement \textbf\{L\}earning from
\textbf\{AI\} \textbf\{F\}eedback for video MLLMs\} (\textbf\{Iter-W2S-RLAIF\}), a
framework that gradually enhances MLLMs' alignment capabilities by iteratively
updating the reference model and performing parameter extrapolation. Finally,
we propose an unbiased and information-complete evaluation scheme in VQA
evaluation. Experiments demonstrate that MMAIP-V is beneficial for MLLMs in
preference learning and Iter-W2S-RLAIF fully exploits the alignment information
in MMAIP-V. We believe that the proposed automatic VQA preference data
generation pipeline based on AI feedback can greatly promote future work in the
MLLMs alignment. \textbf\{Code and dataset are available\}
\href\{https://anonymous.4open.science/r/MMAIP-V_Iter-W2S-RLAIF-702F\}\{MMAIP-V\_Iter-W2S-RLAIF-702F\}.