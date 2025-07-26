---
layout: publication
title: 'Counterfactual VQA: A Cause-effect Look At Language Bias'
authors: Yulei Niu, Kaihua Tang, Hanwang Zhang, Zhiwu Lu, Xian-sheng Hua, Ji-rong
  Wen
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: niu2020counterfactual
citations: 327
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.04315'}]
tags: ["CVPR"]
short_authors: Niu et al.
---
VQA models may tend to rely on language bias as a shortcut and thus fail to
sufficiently learn the multi-modal knowledge from both vision and language.
Recent debiasing methods proposed to exclude the language prior during
inference. However, they fail to disentangle the "good" language context and
"bad" language bias from the whole. In this paper, we investigate how to
mitigate language bias in VQA. Motivated by causal effects, we proposed a novel
counterfactual inference framework, which enables us to capture the language
bias as the direct causal effect of questions on answers and reduce the
language bias by subtracting the direct language effect from the total causal
effect. Experiments demonstrate that our proposed counterfactual inference
framework 1) is general to various VQA backbones and fusion strategies, 2)
achieves competitive performance on the language-bias sensitive VQA-CP dataset
while performs robustly on the balanced VQA v2 dataset without any augmented
data. The code is available at https://github.com/yuleiniu/cfvqa.