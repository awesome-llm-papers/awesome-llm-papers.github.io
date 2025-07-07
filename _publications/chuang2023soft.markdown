---
layout: publication
title: 'Spec: A Soft Prompt-based Calibration On Performance Variability Of Large
  Language Model In Clinical Notes Summarization'
authors: Yu-neng Chuang, Ruixiang Tang, Xiaoqian Jiang, Xia Hu
conference: Arxiv
year: 2023
citations: 15
bibkey: chuang2023soft
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13035'}]
tags: [Prompting]
---
Electronic health records (EHRs) store an extensive array of patient
information, encompassing medical histories, diagnoses, treatments, and test
outcomes. These records are crucial for enabling healthcare providers to make
well-informed decisions regarding patient care. Summarizing clinical notes
further assists healthcare professionals in pinpointing potential health risks
and making better-informed decisions. This process contributes to reducing
errors and enhancing patient outcomes by ensuring providers have access to the
most pertinent and current patient data. Recent research has shown that
incorporating prompts with large language models (LLMs) substantially boosts
the efficacy of summarization tasks. However, we show that this approach also
leads to increased output variance, resulting in notably divergent outputs even
when prompts share similar meanings. To tackle this challenge, we introduce a
model-agnostic Soft Prompt-Based Calibration (SPeC) pipeline that employs soft
prompts to diminish variance while preserving the advantages of prompt-based
summarization. Experimental findings on multiple clinical note tasks and LLMs
indicate that our method not only bolsters performance but also effectively
curbs variance for various LLMs, providing a more uniform and dependable
solution for summarizing vital medical information.