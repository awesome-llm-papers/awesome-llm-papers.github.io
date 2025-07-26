---
layout: publication
title: 'Kanana: Compute-efficient Bilingual Language Models'
authors: Kanana Llm Team, Yunju Bak, Hojin Lee, Minho Ryu, Jiyeon Ham, Seungjae Jung,
  Daniel Wontae Nam, Taegyeong Eo, Donghun Lee, Doohae Jung, Boseop Kim, Nayeon Kim,
  Jaesun Park, Hyunho Kim, Hyunwoong Ko, Changmin Lee, Kyoung-woon On, Seulye Baeg,
  Junrae Cho, Sunghee Jung, Jieun Kang, Eunggyun Kim, Eunhwa Kim, Byeongil Ko, Daniel
  Lee, Minchul Lee, Miok Lee, Shinbok Lee, Gaeun Seo
conference: No Venue
year: 2025
bibkey: team2025kanana
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67bfe1c04426925c82fe59a1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.18934'}]
tags: ["Efficiency"]
short_authors: Team et al.
---
We introduce Kanana, a series of bilingual language models that demonstrate exceeding performance in Korean and competitive performance in English. The computational cost of Kanana is significantly lower than that of state-of-the-art models of similar size. The report details the techniques employed during pre-training to achieve compute-efficient yet competitive models, including high quality data filtering, staged pre-training, depth up-scaling, and pruning and distillation. Furthermore, the report outlines the methodologies utilized during the post-training of the Kanana models, encompassing supervised fine-tuning and preference optimization, aimed at enhancing their capability for seamless interaction with users. Lastly, the report elaborates on plausible approaches used for language model adaptation to specific scenarios, such as embedding, retrieval augmented generation, and function calling. The Kanana model series spans from 2.1B to 32.5B parameters with 2.1B models (base, instruct, embedding) publicly released to promote research on Korean language models.

https://huggingface.co/discussions/paper/67bfe1c04426925c82fe59a1