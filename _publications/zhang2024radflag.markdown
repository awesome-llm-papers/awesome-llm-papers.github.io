---
layout: publication
title: 'Radflag: A Black-box Hallucination Detection Method For Medical Vision Language
  Models'
authors: Zhang et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: zhang2024radflag
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.00299'}]
tags: [Reinforcement Learning, EMNLP]
---
Generating accurate radiology reports from medical images is a clinically
important but challenging task. While current Vision Language Models (VLMs)
show promise, they are prone to generating hallucinations, potentially
compromising patient care. We introduce RadFlag, a black-box method to enhance
the accuracy of radiology report generation. Our method uses a sampling-based
flagging technique to find hallucinatory generations that should be removed. We
first sample multiple reports at varying temperatures and then use a Large
Language Model (LLM) to identify claims that are not consistently supported
across samples, indicating that the model has low confidence in those claims.
Using a calibrated threshold, we flag a fraction of these claims as likely
hallucinations, which should undergo extra review or be automatically rejected.
Our method achieves high precision when identifying both individual
hallucinatory sentences and reports that contain hallucinations. As an
easy-to-use, black-box system that only requires access to a model's
temperature parameter, RadFlag is compatible with a wide range of radiology
report generation models and has the potential to broadly improve the quality
of automated radiology reporting.