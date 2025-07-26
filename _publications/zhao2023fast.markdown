---
layout: publication
title: Fast Segment Anything
authors: Xu Zhao, Wenchao Ding, Yongqi An, Yinglong Du, Tao Yu, Min Li, Ming Tang,
  Jinqiao Wang
conference: No Venue
year: 2023
bibkey: zhao2023fast
additional_links: [{name: Code, url: 'https://github.com/CASIA-IVA-Lab/FastSAM'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6493c9fb897021202a0d0e4e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2306.12156'}]
tags: ["Applications", "Datasets", "Has Code", "Model Architecture", "Prompting"]
short_authors: Zhao et al.
---
The recently proposed segment anything model (SAM) has made a significant influence in many computer vision tasks. It is becoming a foundation step for many high-level tasks, like image segmentation, image caption, and image editing. However, its huge computation costs prevent it from wider applications in industry scenarios. The computation mainly comes from the Transformer architecture at high-resolution inputs. In this paper, we propose a speed-up alternative method for this fundamental task with comparable performance. By reformulating the task as segments-generation and prompting, we find that a regular CNN detector with an instance segmentation branch can also accomplish this task well. Specifically, we convert this task to the well-studied instance segmentation task and directly train the existing instance segmentation method using only 1/50 of the SA-1B dataset published by SAM authors. With our method, we achieve a comparable performance with the SAM method at 50 times higher run-time speed. We give sufficient experimental results to demonstrate its effectiveness. The codes and demos will be released at https://github.com/CASIA-IVA-Lab/FastSAM.

https://huggingface.co/discussions/paper/6493c9fb897021202a0d0e4e