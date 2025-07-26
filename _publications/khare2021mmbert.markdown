---
layout: publication
title: 'MMBERT: Multimodal BERT Pretraining For Improved Medical VQA'
authors: Yash Khare, Viraj Bagal, Minesh Mathew, Adithi Devi, U Deva Priyakumar, Cv
  Jawahar
conference: 2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)
year: 2021
bibkey: khare2021mmbert
citations: 95
additional_links: [{name: Code, url: 'https://github.com/VirajBagal/MMBERT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2104.01394'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Khare et al.
---
Images in the medical domain are fundamentally different from the general
domain images. Consequently, it is infeasible to directly employ general domain
Visual Question Answering (VQA) models for the medical domain. Additionally,
medical images annotation is a costly and time-consuming process. To overcome
these limitations, we propose a solution inspired by self-supervised
pretraining of Transformer-style architectures for NLP, Vision and Language
tasks. Our method involves learning richer medical image and text semantic
representations using Masked Language Modeling (MLM) with image features as the
pretext task on a large medical image+caption dataset. The proposed solution
achieves new state-of-the-art performance on two VQA datasets for radiology
images -- VQA-Med 2019 and VQA-RAD, outperforming even the ensemble models of
previous best solutions. Moreover, our solution provides attention maps which
help in model interpretability. The code is available at
https://github.com/VirajBagal/MMBERT