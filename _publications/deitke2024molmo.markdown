---
layout: publication
title: 'Molmo And Pixmo: Open Weights And Open Data For State-of-the-art Multimodal
  Models'
authors: Matt Deitke, Christopher Clark, Sangho Lee, Rohun Tripathi, Yue Yang, Jae
  Sung Park, Mohammadreza Salehi, Niklas Muennighoff, Kyle Lo, Luca Soldaini, Jiasen
  Lu, Taira Anderson, Erin Bransom, Kiana Ehsani, Huong Ngo, Yensung Chen, Ajay Patel,
  Mark Yatskar, Chris Callison-burch, Andrew Head, Rose Hendrix, Favyen Bastani, Eli
  Vanderbilt, Nathan Lambert, Yvonne Chou, Arnavi Chheda, Jenna Sparks, Sam Skjonsberg,
  Michael Schmitz, Aaron Sarnat, Byron Bischoff, Pete Walsh, Chris Newell, Piper Wolters,
  Tanmay Gupta, Kuo-hao Zeng, Jon Borchardt, Dirk Groeneveld, Jen Dumas, Crystal Nam,
  Sophie Lebrecht, Caitlin Wittlif, Carissa Schoenick, Oscar Michel, Ranjay Krishna,
  Luca Weihs, Noah A. Smith, Hannaneh Hajishirzi, Ross Girshick, Ali Farhadi, Aniruddha
  Kembhavi
conference: No Venue
year: 2024
bibkey: deitke2024molmo
additional_links: [{name: Code, url: 'https://molmo.allenai.org'}, {name: Code, url: 'https://huggingface.co/discussions/paper/66f4c5cab26f10a31416f579'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.17146'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Deitke et al.
---
Today's most advanced multimodal models remain proprietary. The strongest open-weight models rely heavily on synthetic data from proprietary VLMs to achieve good performance, effectively distilling these closed models into open ones. As a result, the community is still missing foundational knowledge about how to build performant VLMs from scratch. We present Molmo, a new family of VLMs that are state-of-the-art in their class of openness. Our key innovation is a novel, highly detailed image caption dataset collected entirely from human annotators using speech-based descriptions. To enable a wide array of user interactions, we also introduce a diverse dataset mixture for fine-tuning that includes in-the-wild Q&A and innovative 2D pointing data. The success of our approach relies on careful choices for the model architecture details, a well-tuned training pipeline, and, most critically, the quality of our newly collected datasets, all of which will be released. The best-in-class 72B model within the Molmo family not only outperforms others in the class of open weight and data models but also compares favorably against proprietary systems like GPT-4o, Claude 3.5, and Gemini 1.5 on both academic benchmarks and human evaluation. We will be releasing all of our model weights, captioning and fine-tuning data, and source code in the near future. Select model weights, inference code, and demo are available at https://molmo.allenai.org.

https://huggingface.co/discussions/paper/66f4c5cab26f10a31416f579