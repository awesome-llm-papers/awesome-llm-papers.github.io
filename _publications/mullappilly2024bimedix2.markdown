---
layout: publication
title: 'Bimedix2: Bio-medical Expert LMM For Diverse Medical Modalities'
authors: Sahal Shaji Mullappilly, Mohammed Irfan Kurpath, Sara Pieri, Saeed Yahya
  Alseiari, Shanavas Cholakkal, Khaled Aldahmani, Fahad Khan, Rao Anwer, Salman Khan,
  Timothy Baldwin, Hisham Cholakkal
conference: No Venue
year: 2024
bibkey: mullappilly2024bimedix2
additional_links: [{name: Code, url: 'https://github.com/mbzuai-oryx/BiMediX2'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/675ee6f0e6d71589c3c62db4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.07769'}]
tags: ["Applications", "Model Architecture"]
short_authors: Mullappilly et al.
---
This paper introduces BiMediX2, a bilingual (Arabic-English) Bio-Medical EXpert Large Multimodal Model (LMM) with a unified architecture that integrates text and visual modalities, enabling advanced image understanding and medical applications. BiMediX2 leverages the Llama3.1 architecture and integrates text and visual capabilities to facilitate seamless interactions in both English and Arabic, supporting text-based inputs and multi-turn conversations involving medical images. The model is trained on an extensive bilingual healthcare dataset consisting of 1.6M samples of diverse medical interactions for both text and image modalities, mixed in Arabic and English. We also propose the first bilingual GPT-4o based medical LMM benchmark named BiMed-MBench. BiMediX2 is benchmarked on both text-based and image-based tasks, achieving state-of-the-art performance across several medical benchmarks. It outperforms recent state-of-the-art models in medical LLM evaluation benchmarks. Our model also sets a new benchmark in multimodal medical evaluations with over 9% improvement in English and over 20% in Arabic evaluations. Additionally, it surpasses GPT-4 by around 9% in UPHILL factual accuracy evaluations and excels in various medical Visual Question Answering, Report Generation, and Report Summarization tasks. The project page including source code and the trained model, is available at https://github.com/mbzuai-oryx/BiMediX2.

https://huggingface.co/discussions/paper/675ee6f0e6d71589c3c62db4