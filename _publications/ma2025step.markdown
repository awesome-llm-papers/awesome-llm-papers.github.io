---
layout: publication
title: 'Step-video-t2v Technical Report: The Practice, Challenges, And Future Of Video
  Foundation Model'
authors: Guoqing Ma, Haoyang Huang, Kun Yan, Liangyu Chen, Nan Duan, Shengming Yin,
  Changyi Wan, Ranchen Ming, Xiaoniu Song, Xing Chen, Yu Zhou, Deshan Sun, Deyu Zhou,
  Jian Zhou, Kaijun Tan, Kang An, Mei Chen, Wei Ji, Qiling Wu, Wen Sun, Xin Han, Yanan
  Wei, Zheng Ge, Aojie Li, Bin Wang, Bizhu Huang, Bo Wang, Brian Li, Changxing Miao,
  Chen Xu, Chenfei Wu, Chenguang Yu, Dapeng Shi, Dingyuan Hu, Enle Liu, Gang Yu, Ge
  Yang, Guanzhe Huang, Gulin Yan, Haiyang Feng, Hao Nie, Haonan Jia, Hanpeng Hu, Hanqi
  Chen, Haolong Yan, Heng Wang, Hongcheng Guo, Huilin Xiong, Huixin Xiong, Jiahao
  Gong, Jianchang Wu, Jiaoren Wu, Jie Wu, Jie Yang, Jiashuai Liu, Jiashuo Li, Jingyang
  Zhang, Junjing Guo, Junzhe Lin, Kaixiang Li, Lei Liu, Lei Xia, Liang Zhao, Liguo
  Tan, Liwen Huang, Liying Shi, Ming Li, Mingliang Li, Muhua Cheng, Na Wang, Qiaohui
  Chen, Qinglin He, Qiuyan Liang, Quan Sun, Ran Sun, Rui Wang, Shaoliang Pang, Shiliang
  Yang, Sitong Liu, Siqi Liu, Shuli Gao, Tiancheng Cao, Tianyu Wang, Weipeng Ming,
  Wenqing He, Xu Zhao, Xuelin Zhang, Xianfang Zeng, Xiaojia Liu, Xuan Yang, Yaqi Dai,
  Yanbo Yu, Yang Li, Yineng Deng, Yingming Wang, Yilei Wang, Yuanwei Lu, Yu Chen,
  Yu Luo, Yuchu Luo, Yuhe Yin, Yuheng Feng, Yuxiang Yang, Zecheng Tang, Zekai Zhang,
  Zidong Yang, Binxing Jiao, Jiansheng Chen, Jing Li, Shuchang Zhou, Xiangyu Zhang,
  Xinhao Zhang, Yibo Zhu, Heung-yeung Shum, Daxin Jiang
conference: No Venue
year: 2025
bibkey: ma2025step
additional_links: [{name: Code, url: 'https://github.com/stepfun-ai/Step-Video-T2V'},
  {name: Code, url: 'https://yuewen.cn/videos'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67b2a7357a49eaea082b9fbf'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.10248'}]
tags: ["Evaluation", "Has Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Ma et al.
---
We present Step-Video-T2V, a state-of-the-art text-to-video pre-trained model with 30B parameters and the ability to generate videos up to 204 frames in length. A deep compression Variational Autoencoder, Video-VAE, is designed for video generation tasks, achieving 16x16 spatial and 8x temporal compression ratios, while maintaining exceptional video reconstruction quality. User prompts are encoded using two bilingual text encoders to handle both English and Chinese. A DiT with 3D full attention is trained using Flow Matching and is employed to denoise input noise into latent frames. A video-based DPO approach, Video-DPO, is applied to reduce artifacts and improve the visual quality of the generated videos. We also detail our training strategies and share key observations and insights. Step-Video-T2V's performance is evaluated on a novel video generation benchmark, Step-Video-T2V-Eval, demonstrating its state-of-the-art text-to-video quality when compared with both open-source and commercial engines. Additionally, we discuss the limitations of current diffusion-based model paradigm and outline future directions for video foundation models. We make both Step-Video-T2V and Step-Video-T2V-Eval available at https://github.com/stepfun-ai/Step-Video-T2V. The online version can be accessed from https://yuewen.cn/videos as well. Our goal is to accelerate the innovation of video foundation models and empower video content creators.

https://huggingface.co/discussions/paper/67b2a7357a49eaea082b9fbf