---
layout: publication
title: 'Mm-ifengine: Towards Multimodal Instruction Following'
authors: Shengyuan Ding, Shenxi Wu, Xiangyu Zhao, Yuhang Zang, Haodong Duan, Xiaoyi
  Dong, Pan Zhang, Yuhang Cao, Dahua Lin, Jiaqi Wang
conference: No Venue
year: 2025
bibkey: ding2025mm
additional_links: [{name: Code, url: 'https://github.com/SYuan03/MM-IFEngine'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/67f8914816d43f88b3177fa7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.07957'}]
tags: ["Has Code", "Instruction Following"]
short_authors: Ding et al.
---
The Instruction Following (IF) ability measures how well Multi-modal Large Language Models (MLLMs) understand exactly what users are telling them and whether they are doing it right. Existing multimodal instruction following training data is scarce, the benchmarks are simple with atomic instructions, and the evaluation strategies are imprecise for tasks demanding exact output constraints. To address this, we present MM-IFEngine, an effective pipeline to generate high-quality image-instruction pairs. Our MM-IFEngine pipeline yields large-scale, diverse, and high-quality training data MM-IFInstruct-23k, which is suitable for Supervised Fine-Tuning (SFT) and extended as MM-IFDPO-23k for Direct Preference Optimization (DPO). We further introduce MM-IFEval, a challenging and diverse multi-modal instruction-following benchmark that includes (1) both compose-level constraints for output responses and perception-level constraints tied to the input images, and (2) a comprehensive evaluation pipeline incorporating both rule-based assessment and judge model. We conduct SFT and DPO experiments and demonstrate that fine-tuning MLLMs on MM-IFInstruct-23k and MM-IFDPO-23k achieves notable gains on various IF benchmarks, such as MM-IFEval (+10.2%), MIA (+7.6%), and IFEval (+12.3%). The full data and evaluation code will be released on https://github.com/SYuan03/MM-IFEngine.

https://huggingface.co/discussions/paper/67f8914816d43f88b3177fa7