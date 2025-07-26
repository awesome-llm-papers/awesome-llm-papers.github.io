---
layout: publication
title: 'Dolma: An Open Corpus Of Three Trillion Tokens For Language Model Pretraining
  Research'
authors: Luca Soldaini, Rodney Kinney, Akshita Bhagia, Dustin Schwenk, David Atkinson,
  Russell Authur, Ben Bogin, Khyathi Chandu, Jennifer Dumas, Yanai Elazar, Valentin
  Hofmann, Ananya Harsh Jha, Sachin Kumar, Li Lucy, Xinxi Lyu, Nathan Lambert, Ian
  Magnusson, Jacob Morrison, Niklas Muennighoff, Aakanksha Naik, Crystal Nam, Matthew
  E. Peters, Abhilasha Ravichander, Kyle Richardson, Zejiang Shen, Emma Strubell,
  Nishant Subramani, Oyvind Tafjord, Pete Walsh, Luke Zettlemoyer, Noah A. Smith,
  Hannaneh Hajishirzi, Iz Beltagy, Dirk Groeneveld, Jesse Dodge, Kyle Lo
conference: No Venue
year: 2024
bibkey: soldaini2024dolma
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65bc5db7c6dea60b6b735ebd'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.00159'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Soldaini et al.
---
Language models have become a critical technology to tackling a wide range of natural language processing tasks, yet many details about how the best-performing language models were developed are not reported. In particular, information about their pretraining corpora is seldom discussed: commercial language models rarely provide any information about their data; even open models rarely release datasets they are trained on, or an exact recipe to reproduce them. As a result, it is challenging to conduct certain threads of language modeling research, such as understanding how training data impacts model capabilities and shapes their limitations. To facilitate open research on language model pretraining, we release Dolma, a three trillion tokens English corpus, built from a diverse mixture of web content, scientific papers, code, public-domain books, social media, and encyclopedic materials. In addition, we open source our data curation toolkit to enable further experimentation and reproduction of our work. In this report, we document Dolma, including its design principles, details about its construction, and a summary of its contents. We interleave this report with analyses and experimental results from training language models on intermediate states of Dolma to share what we have learned about important data curation practices, including the role of content or quality filters, deduplication, and multi-source mixing. Dolma has been used to train OLMo, a state-of-the-art, open language model and framework designed to build and study the science of language modeling.

https://huggingface.co/discussions/paper/65bc5db7c6dea60b6b735ebd