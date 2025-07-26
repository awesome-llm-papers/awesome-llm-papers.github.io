---
layout: publication
title: 'MLP-KAN: Unifying Deep Representation And Function Learning'
authors: Yunhong He, Yifeng Xie, Zhengqing Yuan, Lichao Sun
conference: No Venue
year: 2024
bibkey: he2024mlp
additional_links: [{name: Code, url: 'https://github.com/DLYuanGod/MLP-KAN'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6704617783f1ca2d2dccb6b0'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.03027'}]
tags: ["Model Architecture"]
short_authors: He et al.
---
Recent advancements in both representation learning and function learning have demonstrated substantial promise across diverse domains of artificial intelligence. However, the effective integration of these paradigms poses a significant challenge, particularly in cases where users must manually decide whether to apply a representation learning or function learning model based on dataset characteristics. To address this issue, we introduce MLP-KAN, a unified method designed to eliminate the need for manual model selection. By integrating Multi-Layer Perceptrons (MLPs) for representation learning and Kolmogorov-Arnold Networks (KANs) for function learning within a Mixture-of-Experts (MoE) architecture, MLP-KAN dynamically adapts to the specific characteristics of the task at hand, ensuring optimal performance. Embedded within a transformer-based framework, our work achieves remarkable results on four widely-used datasets across diverse domains. Extensive experimental evaluation demonstrates its superior versatility, delivering competitive performance across both deep representation and function learning tasks. These findings highlight the potential of MLP-KAN to simplify the model selection process, offering a comprehensive, adaptable solution across various domains. Our code and weights are available at https://github.com/DLYuanGod/MLP-KAN.

https://huggingface.co/discussions/paper/6704617783f1ca2d2dccb6b0