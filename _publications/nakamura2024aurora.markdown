---
layout: publication
title: 'Aurora-m: The First Open Source Multilingual Language Model Red-teamed According
  To The U.S. Executive Order'
authors: Taishi Nakamura, Mayank Mishra, Simone Tedeschi, Yekun Chai, Jason T Stillerman,
  Felix Friedrich, Prateek Yadav, Tanmay Laud, Vu Minh Chien, Terry Yue Zhuo, Diganta
  Misra, Ben Bogin, Xuan-son Vu, Marzena Karpinska, Arnav Varma Dantuluri, Wojciech
  Kusa, Tommaso Furlanello, Rio Yokota, Niklas Muennighoff, Suhas Pai, Tosin Adewumi,
  Veronika Laippala, Xiaozhe Yao, Adalberto Junior, Alpay Ariyak, Aleksandr Drozd,
  Jordan Clive, Kshitij Gupta, Liangyu Chen, Qi Sun, Ken Tsui, Noah Persaud, Nour
  Fahmy, Tianlong Chen, Mohit Bansal, Nicolo Monti, Tai Dang, Ziyang Luo, Tien-tung
  Bui, Roberto Navigli, Virendra Mehta, Matthew Blumberg, Victor May, Huu Nguyen,
  Sampo Pyysalo
conference: No Venue
year: 2024
bibkey: nakamura2024aurora
additional_links: [{name: Code, url: 'https://huggingface.co/collections/aurora-m/aurora-m-models-65fdfdff62471e09812f5407'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/660b5b0cecc38ac2450f237f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.00399'}]
tags: ["Applications", "Ethics & Fairness", "Security", "Training Techniques"]
short_authors: Nakamura et al.
---
Pretrained language models underpin several AI applications, but their high computational cost for training limits accessibility. Initiatives such as BLOOM and StarCoder aim to democratize access to pretrained models for collaborative community development. However, such existing models face challenges: limited multilingual capabilities, continual pretraining causing catastrophic forgetting, whereas pretraining from scratch is computationally expensive, and compliance with AI safety and development laws. This paper presents Aurora-M, a 15B parameter multilingual open-source model trained on English, Finnish, Hindi, Japanese, Vietnamese, and code. Continually pretrained from StarCoderPlus on 435 billion additional tokens, Aurora-M surpasses 2 trillion tokens in total training token count. It is the first open-source multilingual model fine-tuned on human-reviewed safety instructions, thus aligning its development not only with conventional red-teaming considerations, but also with the specific concerns articulated in the Biden-Harris Executive Order on the Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence. Aurora-M is rigorously evaluated across various tasks and languages, demonstrating robustness against catastrophic forgetting and outperforming alternatives in multilingual settings, particularly in safety evaluations. To promote responsible open-source LLM development, Aurora-M and its variants are released at https://huggingface.co/collections/aurora-m/aurora-m-models-65fdfdff62471e09812f5407 .

https://huggingface.co/discussions/paper/660b5b0cecc38ac2450f237f