---
layout: publication
title: 'Genius: A Generalizable And Purely Unsupervised Self-training Framework For
  Advanced Reasoning'
authors: Fangzhi Xu, Hang Yan, Chang Ma, Haiteng Zhao, Qiushi Sun, Kanzhi Cheng, Junxian
  He, Jun Liu, Zhiyong Wu
conference: No Venue
year: 2025
bibkey: xu2025genius
additional_links: [{name: Code, url: 'https://github.com/xufangzhi/Genius'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67fcb72a4a92187863e8061b'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2504.08672'}]
tags: ["Training Techniques"]
short_authors: Xu et al.
---
Advancing LLM reasoning skills has captivated wide interest. However, current post-training techniques rely heavily on supervisory signals, such as outcome supervision or auxiliary reward models, which face the problem of scalability and high annotation costs. This motivates us to enhance LLM reasoning without the need for external supervision. We introduce a generalizable and purely unsupervised self-training framework, named Genius. Without external auxiliary, Genius requires to seek the optimal response sequence in a stepwise manner and optimize the LLM. To explore the potential steps and exploit the optimal ones, Genius introduces a stepwise foresight re-sampling strategy to sample and estimate the step value by simulating future outcomes. Further, we recognize that the unsupervised setting inevitably induces the intrinsic noise and uncertainty. To provide a robust optimization, we propose an advantage-calibrated optimization (ACO) loss function to mitigate estimation inconsistencies. Combining these techniques together, Genius provides an advanced initial step towards self-improve LLM reasoning with general queries and without supervision, revolutionizing reasoning scaling laws given the vast availability of general queries. The code will be released at https://github.com/xufangzhi/Genius.

https://huggingface.co/discussions/paper/67fcb72a4a92187863e8061b