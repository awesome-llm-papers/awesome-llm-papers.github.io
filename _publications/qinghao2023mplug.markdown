---
layout: publication
title: 'Mplug-owl: Modularization Empowers Large Language Models With Multimodality'
authors: [qinghao Ye, haiyang Xu, guohai Xu, jiabo Ye, ming Yan, yiyang Zhou, junyang
    Wang, anwen Hu, pengcheng Shi, yaya Shi, chenliang Li, yuanhong Xu, hehong Chen,
  junfeng Tian, qi Qian, ji Zhang, fei Huang, jingren Zhou]
conference: Arxiv
year: 2023
bibkey: qinghao2023mplug
citations: 130
additional_links: [{name: Code, url: 'https://github.com/X-PLUG/mPLUG-Owl'}, {name: Code,
    url: 'https://www.modelscope.cn/studios/damo/mPLUG-Owl'}, {name: Paper, url: 'http://arxiv.org/abs/2304.14178v3'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Has Code", "Training Techniques"]
short_authors: Ye et al.
---
Large language models (LLMs) have demonstrated impressive zero-shot abilities
on a variety of open-ended tasks, while recent research has also explored the
use of LLMs for multi-modal generation. In this study, we introduce mPLUG-Owl,
a novel training paradigm that equips LLMs with multi-modal abilities through
modularized learning of foundation LLM, a visual knowledge module, and a visual
abstractor module. This approach can support multiple modalities and facilitate
diverse unimodal and multimodal abilities through modality collaboration. The
training paradigm of mPLUG-Owl involves a two-stage method for aligning image
and text, which learns visual knowledge with the assistance of LLM while
maintaining and even improving the generation abilities of LLM. In the first
stage, the visual knowledge module and abstractor module are trained with a
frozen LLM module to align the image and text. In the second stage,
language-only and multi-modal supervised datasets are used to jointly fine-tune
a low-rank adaption (LoRA) module on LLM and the abstractor module by freezing
the visual knowledge module. We carefully build a visually-related instruction
evaluation set OwlEval. Experimental results show that our model outperforms
existing multi-modal models, demonstrating mPLUG-Owl's impressive instruction
and visual understanding ability, multi-turn conversation ability, and
knowledge reasoning ability. Besides, we observe some unexpected and exciting
abilities such as multi-image correlation and scene text understanding, which
makes it possible to leverage it for harder real scenarios, such as vision-only
document comprehension. Our code, pre-trained model, instruction-tuned models,
and evaluation set are available at https://github.com/X-PLUG/mPLUG-Owl. The
online demo is available at https://www.modelscope.cn/studios/damo/mPLUG-Owl.