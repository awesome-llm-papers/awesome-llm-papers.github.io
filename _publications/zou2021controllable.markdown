---
layout: publication
title: Controllable Generation From Pre-trained Language Models Via Inverse Prompting
authors: Xu Zou et al.
conference: Arxiv
year: 2021
citations: 18
bibkey: zou2021controllable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.10685'}, {name: Code,
    url: 'https://pretrain.aminer.cn/apps/poetry.html,'}, {name: Code, url: 'https://pretrain.aminer.cn/app/qa'},
  {name: Code, url: 'https://github.com/THUDM/InversePrompting'}]
tags: [Language Modeling, Has Code, Prompting]
---
Large-scale pre-trained language models have demonstrated strong capabilities
of generating realistic text. However, it remains challenging to control the
generation results. Previous approaches such as prompting are far from
sufficient, which limits the usage of language models. To tackle this
challenge, we propose an innovative method, inverse prompting, to better
control text generation. The core idea of inverse prompting is to use generated
text to inversely predict the prompt during beam search, which enhances the
relevance between the prompt and the generated text and provides better
controllability. Empirically, we pre-train a large-scale Chinese language model
to perform a systematic study using human evaluation on the tasks of
open-domain poem generation and open-domain long-form question answering. Our
results show that our proposed method substantially outperforms the baselines
and that our generation quality is close to human performance on some of the
tasks.
  Narrators can try our poem generation demo at
https://pretrain.aminer.cn/apps/poetry.html, while our QA demo can be found at
https://pretrain.aminer.cn/app/qa. For researchers, the code is provided in
https://github.com/THUDM/InversePrompting.