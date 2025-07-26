---
layout: publication
title: 'MMTEB: Massive Multilingual Text Embedding Benchmark'
authors: "Kenneth Enevoldsen, Isaac Chung, Imene Kerboua, M\xE1rton Kardos, Ashwin\
  \ Mathur, David Stap, Jay Gala, Wissam Siblini, Dominik Krzemi\u0144ski, Genta Indra\
  \ Winata, Saba Sturua, Saiteja Utpala, Mathieu Ciancone, Marion Schaeffer, Gabriel\
  \ Sequeira, Diganta Misra, Shreeya Dhakal, Jonathan Rystr\xF8m, Roman Solomatin,\
  \ \xD6mer \xC7a\u011Fatan, Akash Kundu, Martin Bernstorff, Shitao Xiao, Akshita\
  \ Sukhlecha, Bhavish Pahwa, Rafa\u0142 Po\u015Bwiata, Kranthi Kiran Gv, Shawon Ashraf,\
  \ Daniel Auras, Bj\xF6rn Pl\xFCster, Jan Philipp Harries, Lo\xEFc Magne, Isabelle\
  \ Mohr, Mariya Hendriksen, Dawei Zhu, Hippolyte Gisserot-boukhlef, Tom Aarsen, Jan\
  \ Kostkan, Konrad Wojtasik, Taemin Lee, Marek \u0160uppa, Crystina Zhang, Roberta\
  \ Rocca, Mohammed Hamdy, Andrianos Michail, John Yang, Manuel Faysse, Aleksei Vatolin,\
  \ Nandan Thakur, Manan Dey, Dipam Vasani, Pranjal Chitale, Simone Tedeschi, Nguyen\
  \ Tai, Artem Snegirev, Michael G\xFCnther, Mengzhou Xia, Weijia Shi, Xing Han L\xF9\
  , Jordan Clive, Gayatri Krishnakumar, Anna Maksimova, Silvan Wehrli, Maria Tikhonova,\
  \ Henil Panchal, Aleksandr Abramov, Malte Ostendorff, Zheng Liu, Simon Clematide,\
  \ Lester James Miranda, Alena Fenogenova, Guangyu Song, Ruqiya Bin Safi, Wen-ding\
  \ Li, Alessia Borghini, Federico Cassano, Hongjin Su, Jimmy Lin, Howard Yen, Lasse\
  \ Hansen, Sara Hooker, Chenghao Xiao, Vaibhav Adlakha, Orion Weller, Siva Reddy,\
  \ Niklas Muennighoff"
conference: No Venue
year: 2025
bibkey: enevoldsen2025mmteb
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67b6fa9db544aa153178a69c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.13595'}]
tags: ["Evaluation"]
short_authors: Enevoldsen et al.
---
Text embeddings are typically evaluated on a limited set of tasks, which are constrained by language, domain, and task diversity. To address these limitations and provide a more comprehensive evaluation, we introduce the Massive Multilingual Text Embedding Benchmark (MMTEB) - a large-scale, community-driven expansion of MTEB, covering over 500 quality-controlled evaluation tasks across 250+ languages. MMTEB includes a diverse set of challenging, novel tasks such as instruction following, long-document retrieval, and code retrieval, representing the largest multilingual collection of evaluation tasks for embedding models to date. Using this collection, we develop several highly multilingual benchmarks, which we use to evaluate a representative set of models. We find that while large language models (LLMs) with billions of parameters can achieve state-of-the-art performance on certain language subsets and task categories, the best-performing publicly available model is multilingual-e5-large-instruct with only 560 million parameters. To facilitate accessibility and reduce computational cost, we introduce a novel downsampling method based on inter-task correlation, ensuring a diverse selection while preserving relative model rankings. Furthermore, we optimize tasks such as retrieval by sampling hard negatives, creating smaller but effective splits. These optimizations allow us to introduce benchmarks that drastically reduce computational demands. For instance, our newly introduced zero-shot English benchmark maintains a ranking order similar to the full-scale version but at a fraction of the computational cost.

https://huggingface.co/discussions/paper/67b6fa9db544aa153178a69c