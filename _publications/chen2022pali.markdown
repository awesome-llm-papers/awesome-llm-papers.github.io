---
layout: publication
title: 'Pali: A Jointly-scaled Multilingual Language-image Model'
authors: Xi Chen, Xiao Wang, Soravit Changpinyo, Aj Piergiovanni, Piotr Padlewski,
  Daniel Salz, Sebastian Goodman, Adam Grycner, Basil Mustafa, Lucas Beyer, Alexander
  Kolesnikov, Joan Puigcerver, Nan Ding, Keran Rong, Hassan Akbari, Gaurav Mishra,
  Linting Xue, Ashish Thapliyal, James Bradbury, Weicheng Kuo, Mojtaba Seyedhosseini,
  Chao Jia, Burcu Karagol Ayan, Carlos Riquelme, Andreas Steiner, Anelia Angelova,
  Xiaohua Zhai, Neil Houlsby, Radu Soricut
conference: Arxiv
year: 2022
bibkey: chen2022pali
citations: 156
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.06794'}]
tags: ["Training Techniques"]
short_authors: Chen et al.
---
Effective scaling and a flexible task interface enable large language models
to excel at many tasks. We present PaLI (Pathways Language and Image model), a
model that extends this approach to the joint modeling of language and vision.
PaLI generates text based on visual and textual inputs, and with this interface
performs many vision, language, and multimodal tasks, in many languages. To
train PaLI, we make use of large pre-trained encoder-decoder language models
and Vision Transformers (ViTs). This allows us to capitalize on their existing
capabilities and leverage the substantial cost of training them. We find that
joint scaling of the vision and language components is important. Since
existing Transformers for language are much larger than their vision
counterparts, we train a large, 4-billion parameter ViT (ViT-e) to quantify the
benefits from even larger-capacity vision models. To train PaLI, we create a
large multilingual mix of pretraining tasks, based on a new image-text training
set containing 10B images and texts in over 100 languages. PaLI achieves
state-of-the-art in multiple vision and language tasks (such as captioning,
visual question-answering, scene-text understanding), while retaining a simple,
modular, and scalable design.