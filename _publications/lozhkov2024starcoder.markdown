---
layout: publication
title: 'Starcoder 2 And The Stack V2: The Next Generation'
authors: "Anton Lozhkov, Raymond Li, Loubna Ben Allal, Federico Cassano, Joel Lamy-poirier,\
  \ Nouamane Tazi, Ao Tang, Dmytro Pykhtar, Jiawei Liu, Yuxiang Wei, Tianyang Liu,\
  \ Max Tian, Denis Kocetkov, Arthur Zucker, Younes Belkada, Zijian Wang, Qian Liu,\
  \ Dmitry Abulkhanov, Indraneil Paul, Zhuang Li, Wen-ding Li, Megan Risdal, Jia Li,\
  \ Jian Zhu, Terry Yue Zhuo, Evgenii Zheltonozhskii, Nii Osae Osae Dade, Wenhao Yu,\
  \ Lucas Krau\xDF, Naman Jain, Yixuan Su, Xuanli He, Manan Dey, Edoardo Abati, Yekun\
  \ Chai, Niklas Muennighoff, Xiangru Tang, Muhtasham Oblokulov, Christopher Akiki,\
  \ Marc Marone, Chenghao Mou, Mayank Mishra, Alex Gu, Binyuan Hui, Tri Dao, Armel\
  \ Zebaze, Olivier Dehaene, Nicolas Patry, Canwen Xu, Julian Mcauley, Han Hu, Torsten\
  \ Scholak, Sebastien Paquet, Jennifer Robinson, Carolyn Jane Anderson, Nicolas Chapados,\
  \ Mostofa Patwary, Nima Tajbakhsh, Yacine Jernite, Carlos Mu\xF1oz Ferrandis, Lingming\
  \ Zhang, Sean Hughes, Thomas Wolf, Arjun Guha, Leandro von Werra, Harm de Vries"
conference: No Venue
year: 2024
bibkey: lozhkov2024starcoder
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65e161d606c9c86f25225a8a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.19173'}]
tags: ["Has Code", "Llm For Code"]
short_authors: Lozhkov et al.
---
The BigCode project, an open-scientific collaboration focused on the responsible development of Large Language Models for Code (Code LLMs), introduces StarCoder2. In partnership with Software Heritage (SWH), we build The Stack v2 on top of the digital commons of their source code archive. Alongside the SWH repositories spanning 619 programming languages, we carefully select other high-quality data sources, such as GitHub pull requests, Kaggle notebooks, and code documentation. This results in a training set that is 4x larger than the first StarCoder dataset. We train StarCoder2 models with 3B, 7B, and 15B parameters on 3.3 to 4.3 trillion tokens and thoroughly evaluate them on a comprehensive set of Code LLM benchmarks. We find that our small model, StarCoder2-3B, outperforms other Code LLMs of similar size on most benchmarks, and also outperforms StarCoderBase-15B. Our large model, StarCoder2- 15B, significantly outperforms other models of comparable size. In addition, it matches or outperforms CodeLlama-34B, a model more than twice its size. Although DeepSeekCoder- 33B is the best-performing model at code completion for high-resource languages, we find that StarCoder2-15B outperforms it on math and code reasoning benchmarks, as well as several low-resource languages. We make the model weights available under an OpenRAIL license and ensure full transparency regarding the training data by releasing the SoftWare Heritage persistent IDentifiers (SWHIDs) of the source code data.

https://huggingface.co/discussions/paper/65e161d606c9c86f25225a8a