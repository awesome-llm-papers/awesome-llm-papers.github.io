---
layout: publication
title: 'Longvila: Scaling Long-context Visual Language Models For Long Videos'
authors: Fuzhao Xue, Yukang Chen, Dacheng Li, Qinghao Hu, Ligeng Zhu, Xiuyu Li, Yunhao
  Fang, Haotian Tang, Shang Yang, Zhijian Liu, Ethan He, Hongxu Yin, Pavlo Molchanov,
  Jan Kautz, Linxi Fan, Yuke Zhu, Yao Lu, Song Han
conference: No Venue
year: 2024
bibkey: xue2024longvila
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.10188'}]
tags: ["Memory & Context"]
short_authors: Xue et al.
---
Long-context capability is critical for multi-modal foundation models. We introduce LongVILA, a full-stack solution for long-context vision-language models, including system, model training, and dataset development. On the system side, we introduce the first Multi-Modal Sequence Parallelism (MM-SP) system that enables long-context training and inference, enabling 2M context length training on 256 GPUs. MM-SP is also efficient, being 2.1x - 5.7x faster than Ring-Style Sequence Parallelism and 1.1x - 1.4x faster than Megatron-LM in text-only settings. Moreover, it seamlessly integrates with Hugging Face Transformers. For model training, we propose a five-stage pipeline comprising alignment, pre-training, context extension, and long-short joint supervised fine-tuning. Regarding datasets, we meticulously construct large-scale visual language pre-training datasets and long video instruction-following datasets to support our multi-stage training process. The full-stack solution extends the feasible frame number of VILA by a factor of 128 (from 8 to 1024 frames) and improves long video captioning score from 2.00 to 3.26 (1.6x), achieving 99.5% accuracy in 1400-frames video (274k context length) needle in a haystack. LongVILA-8B also demonstrates a consistent improvement in performance on long videos within the VideoMME benchmark as the video frames increase.

https://huggingface.co/discussions/paper/66c41183ea476bea05da1adf