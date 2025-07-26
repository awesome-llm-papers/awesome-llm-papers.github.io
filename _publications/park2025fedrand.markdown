---
layout: publication
title: 'Fedrand: Enhancing Privacy In Federated Learning With Randomized Lora Subparameter
  Updates'
authors: Sangwoo Park, Seanie Lee, Byungjoo Kim, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: park2025fedrand
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.07216'}]
tags: ["Privacy", "Security", "Tools"]
short_authors: Park et al.
---
Federated Learning (FL) is a widely used framework for training models in a decentralized manner, ensuring that the central server does not have direct access to data from local clients. However, this approach may still fail to fully preserve data privacy, as models from local clients are exposed to the central server during the aggregation process. This issue becomes even more critical when training vision-language models (VLMs) with FL, as VLMs can easily memorize training data instances, making them vulnerable to membership inference attacks (MIAs). To address this challenge, we propose the FedRand framework, which avoids disclosing the full set of client parameters. In this framework, each client randomly selects subparameters of Low-Rank Adaptation (LoRA) from the server and keeps the remaining counterparts of the LoRA weights as private parameters. After training both parameters on the client's private dataset, only the non-private client parameters are sent back to the server for aggregation. This approach mitigates the risk of exposing client-side VLM parameters, thereby enhancing data privacy. We empirically validate that FedRand improves robustness against MIAs compared to relevant baselines while achieving accuracy comparable to methods that communicate full LoRA parameters across several benchmark datasets.

https://huggingface.co/discussions/paper/67cfa6fdd77496ce0c154c18