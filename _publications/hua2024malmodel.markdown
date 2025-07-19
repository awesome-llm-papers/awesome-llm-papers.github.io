---
layout: publication
title: 'Malmodel: Hiding Malicious Payload In Mobile Deep Learning Models With Black-box
  Backdoor Attack'
authors: Hua et al.
conference: 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE)
year: 2024
bibkey: hua2024malmodel
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.02659'}]
tags: [Security, Tools, LLM For Code, Applications, LLM for Code, RAG]
---
Mobile malware has become one of the most critical security threats in the
era of ubiquitous mobile computing. Despite the intensive efforts from security
experts to counteract it, recent years have still witnessed a rapid growth of
identified malware samples. This could be partly attributed to the
newly-emerged technologies that may constantly open up under-studied attack
surfaces for the adversaries. One typical example is the recently-developed
mobile machine learning (ML) framework that enables storing and running deep
learning (DL) models on mobile devices. Despite obvious advantages, this new
feature also inadvertently introduces potential vulnerabilities (e.g.,
on-device models may be modified for malicious purposes). In this work, we
propose a method to generate or transform mobile malware by hiding the
malicious payloads inside the parameters of deep learning models, based on a
strategy that considers four factors (layer type, layer number, layer coverage
and the number of bytes to replace). Utilizing the proposed method, we can run
malware in DL mobile applications covertly with little impact on the model
performance (i.e., as little as 0.4% drop in accuracy and at most 39ms latency
overhead).