---
layout: publication
title: Can Prompt Learning Benefit Radiology Report Generation?
authors: Jun Wang, Lixing Zhu, Abhir Bhalerao, Yulan He
conference: Proceedings of the 46th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2023
bibkey: wang2023can
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.16269'}]
tags: ["Prompting", "SIGIR"]
short_authors: Wang et al.
---
Radiology report generation aims to automatically provide clinically
meaningful descriptions of radiology images such as MRI and X-ray. Although
great success has been achieved in natural scene image captioning tasks,
radiology report generation remains challenging and requires prior medical
knowledge. In this paper, we propose PromptRRG, a method that utilizes prompt
learning to activate a pretrained model and incorporate prior knowledge. Since
prompt learning for radiology report generation has not been explored before,
we begin with investigating prompt designs and categorise them based on varying
levels of knowledge: common, domain-specific and disease-enriched prompts.
Additionally, we propose an automatic prompt learning mechanism to alleviate
the burden of manual prompt engineering. This is the first work to
systematically examine the effectiveness of prompt learning for radiology
report generation. Experimental results on the largest radiology report
generation benchmark, MIMIC-CXR, demonstrate that our proposed method achieves
state-of-the-art performance. Code will be available upon the acceptance.