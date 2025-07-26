---
layout: publication
title: 'Paligemma 2: A Family Of Versatile Vlms For Transfer'
authors: "Andreas Steiner, Andr\xE9 Susano Pinto, Michael Tschannen, Daniel Keysers,\
  \ Xiao Wang, Yonatan Bitton, Alexey Gritsenko, Matthias Minderer, Anthony Sherbondy,\
  \ Shangbang Long, Siyang Qin, Reeve Ingle, Emanuele Bugliarello, Sahar Kazemzadeh,\
  \ Thomas Mesnard, Ibrahim Alabdulmohsin, Lucas Beyer, Xiaohua Zhai"
conference: No Venue
year: 2024
bibkey: steiner2024paligemma
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/675159fe74b66f2e014ede63'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.03555'}]
tags: ["Fine-Tuning"]
short_authors: Steiner et al.
---
PaliGemma 2 is an upgrade of the PaliGemma open Vision-Language Model (VLM) based on the Gemma 2 family of language models. We combine the SigLIP-So400m vision encoder that was also used by PaliGemma with the whole range of Gemma 2 models, from the 2B one all the way up to the 27B model. We train these models at three resolutions (224px, 448px, and 896px) in multiple stages to equip them with broad knowledge for transfer via fine-tuning. The resulting family of base models covering different model sizes and resolutions allows us to investigate factors impacting transfer performance (such as learning rate) and to analyze the interplay between the type of task, model size, and resolution. We further increase the number and breadth of transfer tasks beyond the scope of PaliGemma including different OCR-related tasks such as table structure recognition, molecular structure recognition, music score recognition, as well as long fine-grained captioning and radiography report generation, on which PaliGemma 2 obtains state-of-the-art results.

https://huggingface.co/discussions/paper/675159fe74b66f2e014ede63