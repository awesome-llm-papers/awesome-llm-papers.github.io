---
layout: publication
title: 'Transfr: Transferable Federated Recommendation With Pre-trained Language Models'
authors: Zhang et al.
conference: Proceedings of the 44th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2024
bibkey: zhang2024transfr
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.01124'}]
tags: [Training Techniques, Model Architecture, Efficiency And Optimization, SIGIR,
  Fine Tuning, Datasets]
---
Federated recommendations (FRs), facilitating multiple local clients to
collectively learn a global model without disclosing user private data, have
emerged as a prevalent architecture for privacy-preserving recommendations. In
conventional FRs, a dominant paradigm is to utilize discrete identities to
represent users/clients and items, which are subsequently mapped to
domain-specific embeddings to participate in model training. Despite
considerable performance, we reveal three inherent limitations that can not be
ignored in federated settings, i.e., non-transferability across domains,
unavailability in cold-start settings, and potential privacy violations during
federated training. To this end, we propose a transferable federated
recommendation model with universal textual representations, TransFR, which
delicately incorporates the general capabilities empowered by pre-trained
language models and the personalized abilities by fine-tuning local private
data. Specifically, it first learns domain-agnostic representations of items by
exploiting pre-trained models with public textual corpora. To tailor for
federated recommendation, we further introduce an efficient federated
fine-tuning and a local training mechanism. This facilitates personalized local
heads for each client by utilizing their private behavior data. By
incorporating pre-training and fine-tuning within FRs, it greatly improves the
adaptation efficiency transferring to a new domain and the generalization
capacity to address cold-start issues. Through extensive experiments on several
datasets, we demonstrate that our TransFR model surpasses several
state-of-the-art FRs in terms of accuracy, transferability, and privacy.