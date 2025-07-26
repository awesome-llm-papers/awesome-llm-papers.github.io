---
layout: publication
title: Magistral
authors: "Mistral-ai, Abhinav Rastogi, Albert Q. Jiang, Andy Lo, Gabrielle Berrada,\
  \ Guillaume Lample, Jason Rute, Joep Barmentlo, Karmesh Yadav, Kartik Khandelwal,\
  \ Khyathi Raghavi Chandu, L\xE9onard Blier, Lucile Saulnier, Matthieu Dinot, Maxime\
  \ Darrin, Neha Gupta, Roman Soletskyi, Sagar Vaze, Teven Le Scao, Yihan Wang, Adam\
  \ Yang, Alexander H. Liu, Alexandre Sablayrolles, Am\xE9lie H\xE9liou, Am\xE9lie\
  \ Martin, Andy Ehrenberg, Anmol Agarwal, Antoine Roux, Arthur Darcet, Arthur Mensch,\
  \ Baptiste Bout, Baptiste Rozi\xE8re, Baudouin de Monicault, Chris Bamford, Christian\
  \ Wallenwein, Christophe Renaudin, Cl\xE9mence Lanfranchi, Darius Dabert, Devon\
  \ Mizelle, Diego de Las Casas, Elliot Chane-sane, Emilien Fugier, Emma Bou Hanna,\
  \ Gauthier Delerce, Gauthier Guinet, Georgii Novikov, Guillaume Martin, Himanshu\
  \ Jaju, Jan Ludziejewski, Jean-hadrien Chabran, Jean-malo Delignon, Joachim Studnia,\
  \ Jonas Amar, Josselin Somerville Roberts, Julien Denize, Karan Saxena, Kush Jain,\
  \ Lingxiao Zhao, Louis Martin, Luyu Gao, L\xE9lio Renard Lavaud, Marie Pellat, Mathilde\
  \ Guillaumin, Mathis Felardos, Maximilian Augustin, Micka\xEBl Seznec, Nikhil Raghuraman,\
  \ Olivier Duchenne, Patricia Wang, Patrick von Platen, Patryk Saffer, Paul Jacob,\
  \ Paul Wambergue, Paula Kurylowicz, Pavankumar Reddy Muddireddy, Philom\xE8ne Chagniot,\
  \ Pierre Stock, Pravesh Agrawal, Romain Sauvestre, R\xE9mi Delacourt, Sanchit Gandhi,\
  \ Sandeep Subramanian, Shashwat Dalal, Siddharth Gandhi, Soham Ghosh, Srijan Mishra,\
  \ Sumukh Aithal, Szymon Antoniak, Thibault Schueller, Thibaut Lavril, Thomas Robert,\
  \ Thomas Wang, Timoth\xE9e Lacroix, Valeriia Nemychnikova, Victor Paltz, Virgile\
  \ Richard, Wen-ding Li, William Marshall, Xuanyu Zhang, Yunhao Tang"
conference: No Venue
year: 2025
bibkey: 2025magistral
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.10910'}]
tags: ["Instruction Following", "Reinforcement Learning", "Training Techniques"]
short_authors: Mistral-ai et al.
---
We introduce Magistral, Mistral's first reasoning model and our own scalable reinforcement learning (RL) pipeline. Instead of relying on existing implementations and RL traces distilled from prior models, we follow a ground up approach, relying solely on our own models and infrastructure. Notably, we demonstrate a stack that enabled us to explore the limits of pure RL training of LLMs, present a simple method to force the reasoning language of the model, and show that RL on text data alone maintains most of the initial checkpoint's capabilities. We find that RL on text maintains or improves multimodal understanding, instruction following and function calling. We present Magistral Medium, trained for reasoning on top of Mistral Medium 3 with RL alone, and we open-source Magistral Small (Apache 2.0) which further includes cold-start data from Magistral Medium.

https://huggingface.co/discussions/paper/684bbe283b733ba333687152