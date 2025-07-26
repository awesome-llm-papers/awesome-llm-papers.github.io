---
layout: publication
title: GR-3 Technical Report
authors: Chilam Cheang, Sijin Chen, Zhongren Cui, Yingdong Hu, Liqun Huang, Tao Kong,
  Hang Li, Yifeng Li, Yuxiao Liu, Xiao Ma, Hao Niu, Wenxuan Ou, Wanli Peng, Zeyu Ren,
  Haixin Shi, Jiawen Tian, Hongtao Wu, Xin Xiao, Yuyang Xiao, Jiafeng Xu, Yichu Yang
conference: No Venue
year: 2025
bibkey: cheang2025gr
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/687ef5a233947f780d9b4aab'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.15493'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Cheang et al.
---
We report our recent progress towards building generalist robot policies, the development of GR-3. GR-3 is a large-scale vision-language-action (VLA) model. It showcases exceptional capabilities in generalizing to novel objects, environments, and instructions involving abstract concepts. Furthermore, it can be efficiently fine-tuned with minimal human trajectory data, enabling rapid and cost-effective adaptation to new settings. GR-3 also excels in handling long-horizon and dexterous tasks, including those requiring bi-manual manipulation and mobile movement, showcasing robust and reliable performance. These capabilities are achieved through a multi-faceted training recipe that includes co-training with web-scale vision-language data, efficient fine-tuning from human trajectory data collected via VR devices, and effective imitation learning with robot trajectory data. In addition, we introduce ByteMini, a versatile bi-manual mobile robot designed with exceptional flexibility and reliability, capable of accomplishing a wide range of tasks when integrated with GR-3. Through extensive real-world experiments, we show GR-3 surpasses the state-of-the-art baseline method, pi_0, on a wide variety of challenging tasks. We hope GR-3 can serve as a step towards building generalist robots capable of assisting humans in daily life.

https://huggingface.co/discussions/paper/687ef5a233947f780d9b4aab