---
layout: publication
title: 'Ruccod: Towards Automated ICD Coding In Russian'
authors: Aleksandr Nesterov, Andrey Sakhovskiy, Ivan Sviridov, Airat Valiev, Vladimir
  Makharev, Petr Anokhin, Galina Zubkova, Elena Tutubalina
conference: No Venue
year: 2025
bibkey: nesterov2025ruccod
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ced7b471b2e0c1f985fbb3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.21263'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Fine-Tuning", "Model Architecture", "RAG", "Training Techniques"]
short_authors: Nesterov et al.
---
This study investigates the feasibility of automating clinical coding in Russian, a language with limited biomedical resources. We present a new dataset for ICD coding, which includes diagnosis fields from electronic health records (EHRs) annotated with over 10,000 entities and more than 1,500 unique ICD codes. This dataset serves as a benchmark for several state-of-the-art models, including BERT, LLaMA with LoRA, and RAG, with additional experiments examining transfer learning across domains (from PubMed abstracts to medical diagnosis) and terminologies (from UMLS concepts to ICD codes). We then apply the best-performing model to label an in-house EHR dataset containing patient histories from 2017 to 2021. Our experiments, conducted on a carefully curated test set, demonstrate that training with the automated predicted codes leads to a significant improvement in accuracy compared to manually annotated data from physicians. We believe our findings offer valuable insights into the potential for automating clinical coding in resource-limited languages like Russian, which could enhance clinical efficiency and data accuracy in these contexts.

https://huggingface.co/discussions/paper/67ced7b471b2e0c1f985fbb3