---
layout: publication
title: Clinically Accurate Chest X-ray Report Generation
authors: Guanxiong Liu, Tzu-ming Harry Hsu, Matthew Mcdermott, Willie Boag, Wei-hung
  Weng, Peter Szolovits, Marzyeh Ghassemi
conference: Arxiv
year: 2019
bibkey: liu2019clinically
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.02633'}]
tags: ["Datasets", "Evaluation", "Reinforcement Learning"]
short_authors: Liu et al.
---
The automatic generation of radiology reports given medical radiographs has
significant potential to operationally and improve clinical patient care. A
number of prior works have focused on this problem, employing advanced methods
from computer vision and natural language generation to produce readable
reports. However, these works often fail to account for the particular nuances
of the radiology domain, and, in particular, the critical importance of
clinical accuracy in the resulting generated reports. In this work, we present
a domain-aware automatic chest X-ray radiology report generation system which
first predicts what topics will be discussed in the report, then conditionally
generates sentences corresponding to these topics. The resulting system is
fine-tuned using reinforcement learning, considering both readability and
clinical accuracy, as assessed by the proposed Clinically Coherent Reward. We
verify this system on two datasets, Open-I and MIMIC-CXR, and demonstrate that
our model offers marked improvements on both language generation metrics and
CheXpert assessed accuracy over a variety of competitive baselines.