---
layout: publication
title: 'Tinygsm: Achieving >80% On Gsm8k With Small Language Models'
authors: Bingbin Liu, Sebastien Bubeck, Ronen Eldan, Janardhan Kulkarni, Yuanzhi Li,
  Anh Nguyen, Rachel Ward, Yi Zhang
conference: No Venue
year: 2023
bibkey: liu2023tinygsm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2312.09241'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
Small-scale models offer various computational advantages, and yet to which extent size is critical for problem-solving abilities remains an open question. Specifically for solving grade school math, the smallest model size so far required to break the 80% barrier on the GSM8K benchmark remains to be 34B. Our work studies how high-quality datasets may be the key for small language models to acquire mathematical reasoning. We introduce TinyGSM, a synthetic dataset of 12.3M grade school math problems paired with Python solutions, generated fully by GPT-3.5. After finetuning on TinyGSM, we find that a duo of a 1.3B generation model and a 1.3B verifier model can achieve 81.5% accuracy, outperforming existing models that are orders of magnitude larger. This also rivals the performance of the GPT-3.5 ``teacher'' model (77.4%), from which our model's training data is generated. Our approach is simple and has two key components: 1) the high-quality dataset TinyGSM, 2) the use of a verifier, which selects the final outputs from multiple candidate generations.

https://huggingface.co/discussions/paper/657bceea696ec3dda930e4d6