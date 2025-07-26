---
layout: publication
title: 'Mathcoder2: Better Math Reasoning From Continued Pretraining On Model-translated
  Mathematical Code'
authors: Zimu Lu, Aojun Zhou, Ke Wang, Houxing Ren, Weikang Shi, Junting Pan, Mingjie
  Zhan, Hongsheng Li
conference: No Venue
year: 2024
bibkey: lu2024mathcoder2
additional_links: [{name: Code, url: 'https://github.com/mathllm/MathCoder2'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6708bbc1d1c640e5586d2248'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.08196'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Lu et al.
---
Code has been shown to be effective in enhancing the mathematical reasoning abilities of large language models due to its precision and accuracy. Previous works involving continued mathematical pretraining often include code that utilizes math-related packages, which are primarily designed for fields such as engineering, machine learning, signal processing, or module testing, rather than being directly focused on mathematical reasoning. In this paper, we introduce a novel method for generating mathematical code accompanied with corresponding reasoning steps for continued pretraining. Our approach begins with the construction of a high-quality mathematical continued pretraining dataset by incorporating math-related web data, code using mathematical packages, math textbooks, and synthetic data. Next, we construct reasoning steps by extracting LaTeX expressions, the conditions needed for the expressions, and the results of the expressions from the previously collected dataset. Based on this extracted information, we generate corresponding code to accurately capture the mathematical reasoning process. Appending the generated code to each reasoning step results in data consisting of paired natural language reasoning steps and their corresponding code. Combining this data with the original dataset results in a 19.2B-token high-performing mathematical pretraining corpus, which we name MathCode-Pile. Training several popular base models with this corpus significantly improves their mathematical abilities, leading to the creation of the MathCoder2 family of models. All of our data processing and training code is open-sourced, ensuring full transparency and easy reproducibility of the entire data collection and training pipeline. The code is released at https://github.com/mathllm/MathCoder2 .

https://huggingface.co/discussions/paper/6708bbc1d1c640e5586d2248