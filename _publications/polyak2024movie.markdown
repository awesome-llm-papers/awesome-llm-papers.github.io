---
layout: publication
title: 'Movie Gen: A Cast Of Media Foundation Models'
authors: Adam Polyak, Amit Zohar, Andrew Brown, Andros Tjandra, Animesh Sinha, Ann
  Lee, Apoorv Vyas, Bowen Shi, Chih-yao Ma, Ching-yao Chuang, David Yan, Dhruv Choudhary,
  Dingkang Wang, Geet Sethi, Guan Pang, Haoyu Ma, Ishan Misra, Ji Hou, Jialiang Wang,
  Kiran Jagadeesh, Kunpeng Li, Luxin Zhang, Mannat Singh, Mary Williamson, Matt Le,
  Matthew Yu, Mitesh Kumar Singh, Peizhao Zhang, Peter Vajda, Quentin Duval, Rohit
  Girdhar, Roshan Sumbaly, Sai Saketh Rambhatla, Sam Tsai, Samaneh Azadi, Samyak Datta,
  Sanyuan Chen, Sean Bell, Sharadh Ramaswamy, Shelly Sheynin, Siddharth Bhattacharya,
  Simran Motwani, Tao Xu, Tianhe Li, Tingbo Hou, Wei-ning Hsu, Xi Yin, Xiaoliang Dai,
  Yaniv Taigman, Yaqiao Luo, Yen-cheng Liu, Yi-chiao Wu, Yue Zhao, Yuval Kirstain,
  Zecheng He, Zijian He, Albert Pumarola, Ali Thabet, Artsiom Sanakoyeu, Arun Mallya,
  Baishan Guo, Boris Araya, Breena Kerr, Carleigh Wood, Ce Liu, Cen Peng, Dimitry
  Vengertsev, Edgar Schonfeld, Elliot Blanchard, Felix Juefei-xu, Fraylie Nord, Jeff
  Liang, John Hoffman, Jonas Kohler, Kaolin Fire, Karthik Sivakumar, Lawrence Chen,
  Licheng Yu, Luya Gao, Markos Georgopoulos, Rashel Moritz, Sara K. Sampson, Shikai
  Li, Simone Parmeggiani, Steve Fine, Tara Fowler, Vladan Petrovic, Yuming Du
conference: No Venue
year: 2024
bibkey: polyak2024movie
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.13720'}]
tags: ["Evaluation", "Memory & Context", "Model Architecture", "Training Techniques"]
short_authors: Polyak et al.
---
We present Movie Gen, a cast of foundation models that generates high-quality, 1080p HD videos with different aspect ratios and synchronized audio. We also show additional capabilities such as precise instruction-based video editing and generation of personalized videos based on a user's image. Our models set a new state-of-the-art on multiple tasks: text-to-video synthesis, video personalization, video editing, video-to-audio generation, and text-to-audio generation. Our largest video generation model is a 30B parameter transformer trained with a maximum context length of 73K video tokens, corresponding to a generated video of 16 seconds at 16 frames-per-second. We show multiple technical innovations and simplifications on the architecture, latent spaces, training objectives and recipes, data curation, evaluation protocols, parallelization techniques, and inference optimizations that allow us to reap the benefits of scaling pre-training data, model size, and training compute for training large scale media generation models. We hope this paper helps the research community to accelerate progress and innovation in media generation models. All videos from this paper are available at https://go.fb.me/MovieGenResearchVideos.

https://huggingface.co/discussions/paper/6711d97db265bbd413b83410