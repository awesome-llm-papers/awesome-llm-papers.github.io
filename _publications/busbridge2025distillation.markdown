---
layout: publication
title: Distillation Scaling Laws
authors: Dan Busbridge, Amitis Shidani, Floris Weers, Jason Ramapuram, Etai Littwin,
  Russ Webb
conference: No Venue
year: 2025
bibkey: busbridge2025distillation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.08606'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Busbridge et al.
---
We provide a distillation scaling law that estimates distilled model performance based on a compute budget and its allocation between the student and teacher. Our findings reduce the risks associated with using distillation at scale; compute allocation for both the teacher and student models can now be done to maximize student performance. We provide compute optimal distillation recipes for when 1) a teacher exists, or 2) a teacher needs training. If many students are to be distilled, or a teacher already exists, distillation outperforms supervised pretraining until a compute level which grows predictably with student size. If one student is to be distilled and a teacher also needs training, supervised learning should be done instead. Additionally, we provide insights across our large scale study of distillation, which increase our understanding of distillation and inform experimental design.

https://huggingface.co/discussions/paper/67ad77fccd8de299e5049d06