---
layout: publication
title: Token-efficient Long Video Understanding For Multimodal Llms
authors: Jindong Jiang, Xiuyu Li, Zhijian Liu, Muyang Li, Guo Chen, Zhiqi Li, De-an
  Huang, Guilin Liu, Zhiding Yu, Kurt Keutzer, Sungjin Ahn, Jan Kautz, Hongxu Yin,
  Yao Lu, Song Han, Wonmin Byeon
conference: No Venue
year: 2025
bibkey: jiang2025token
additional_links: [{name: Code, url: 'https://research.nvidia.com/labs/lpr/storm'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67ca7bb16d5c2eafede56df1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.04130'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Jiang et al.
---
Recent advances in video-based multimodal large language models (Video-LLMs) have significantly improved video understanding by processing videos as sequences of image frames. However, many existing methods treat frames independently in the vision backbone, lacking explicit temporal modeling, which limits their ability to capture dynamic patterns and efficiently handle long videos. To address these limitations, we introduce STORM (Spatiotemporal TOken Reduction for Multimodal LLMs), a novel architecture incorporating a dedicated temporal encoder between the image encoder and the LLM. Our temporal encoder leverages the Mamba State Space Model to integrate temporal information into image tokens, generating enriched representations that preserve inter-frame dynamics across the entire video sequence. This enriched encoding not only enhances video reasoning capabilities but also enables effective token reduction strategies, including test-time sampling and training-based temporal and spatial pooling, substantially reducing computational demands on the LLM without sacrificing key temporal information. By integrating these techniques, our approach simultaneously reduces training and inference latency while improving performance, enabling efficient and robust video understanding over extended temporal contexts. Extensive evaluations show that STORM achieves state-of-the-art results across various long video understanding benchmarks (more than 5% improvement on MLVU and LongVideoBench) while reducing the computation costs by up to 8times and the decoding latency by 2.4-2.9times for the fixed numbers of input frames. Project page is available at https://research.nvidia.com/labs/lpr/storm

https://huggingface.co/discussions/paper/67ca7bb16d5c2eafede56df1