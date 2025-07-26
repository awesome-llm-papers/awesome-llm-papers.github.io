---
layout: publication
title: Palm 2 Technical Report
authors: "Rohan Anil, Andrew M. Dai, Orhan Firat, Melvin Johnson, Dmitry Lepikhin,\
  \ Alexandre Passos, Siamak Shakeri, Emanuel Taropa, Paige Bailey, Zhifeng Chen,\
  \ Eric Chu, Jonathan H. Clark, Laurent El Shafey, Yanping Huang, Kathy Meier-hellstern,\
  \ Gaurav Mishra, Erica Moreira, Mark Omernick, Kevin Robinson, Sebastian Ruder,\
  \ Yi Tay, Kefan Xiao, Yuanzhong Xu, Yujing Zhang, Gustavo Hernandez Abrego, Junwhan\
  \ Ahn, Jacob Austin, Paul Barham, Jan Botha, James Bradbury, Siddhartha Brahma,\
  \ Kevin Brooks, Michele Catasta, Yong Cheng, Colin Cherry, Christopher A. Choquette-choo,\
  \ Aakanksha Chowdhery, Cl\xE9ment Crepy, Shachi Dave, Mostafa Dehghani, Sunipa Dev,\
  \ Jacob Devlin, Mark D\xEDaz, Nan Du, Ethan Dyer, Vlad Feinberg, Fangxiaoyu Feng,\
  \ Vlad Fienber, Markus Freitag, Xavier Garcia, Sebastian Gehrmann, Lucas Gonzalez,\
  \ Guy Gur-ari, Steven Hand, Hadi Hashemi, Le Hou, Joshua Howland, Andrea Hu, Jeffrey\
  \ Hui, Jeremy Hurwitz, Michael Isard, Abe Ittycheriah, Matthew Jagielski, Wenhao\
  \ Jia, Kathleen Kenealy, Maxim Krikun, Sneha Kudugunta, Chang Lan, Katherine Lee,\
  \ Benjamin Lee, Eric Li, Music Li, Wei Li, Yaguang Li, Jian Li, Hyeontaek Lim, Hanzhao\
  \ Lin, Zhongtao Liu, Frederick Liu, Marcello Maggioni, Aroma Mahendru, Joshua Maynez,\
  \ Vedant Misra, Maysam Moussalem, Zachary Nado, John Nham, Eric Ni, Andrew Nystrom,\
  \ Alicia Parrish, Marie Pellat, Martin Polacek, Alex Polozov, Reiner Pope, Siyuan\
  \ Qiao, Emily Reif, Bryan Richter, Parker Riley, Alex Castro Ros, Aurko Roy, Brennan\
  \ Saeta, Rajkumar Samuel, Renee Shelby, Ambrose Slone, Daniel Smilkov, David R.\
  \ So, Daniel Sohn, Simon Tokumine, Dasha Valter, Vijay Vasudevan, Kiran Vodrahalli,\
  \ Xuezhi Wang, Pidong Wang, Zirui Wang, Tao Wang, John Wieting, Yuhuai Wu, Kelvin\
  \ Xu, Yunhan Xu, Linting Xue, Pengcheng Yin, Jiahui Yu, Qiao Zhang, Steven Zheng,\
  \ Ce Zheng, Weikang Zhou, Denny Zhou, Slav Petrov, Yonghui Wu"
conference: Arxiv
year: 2023
bibkey: anil2023palm
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.10403'}]
tags: ["Efficiency", "Ethics & Fairness", "Evaluation Frameworks", "Model Architecture"]
short_authors: Anil et al.
---
We introduce PaLM 2, a new state-of-the-art language model that has better
multilingual and reasoning capabilities and is more compute-efficient than its
predecessor PaLM. PaLM 2 is a Transformer-based model trained using a mixture
of objectives. Through extensive evaluations on English and multilingual
language, and reasoning tasks, we demonstrate that PaLM 2 has significantly
improved quality on downstream tasks across different model sizes, while
simultaneously exhibiting faster and more efficient inference compared to PaLM.
This improved efficiency enables broader deployment while also allowing the
model to respond faster, for a more natural pace of interaction. PaLM 2
demonstrates robust reasoning capabilities exemplified by large improvements
over PaLM on BIG-Bench and other reasoning tasks. PaLM 2 exhibits stable
performance on a suite of responsible AI evaluations, and enables
inference-time control over toxicity without additional overhead or impact on
other capabilities. Overall, PaLM 2 achieves state-of-the-art performance
across a diverse set of tasks and capabilities.
  When discussing the PaLM 2 family, it is important to distinguish between
pre-trained models (of various sizes), fine-tuned variants of these models, and
the user-facing products that use these models. In particular, user-facing
products typically include additional pre- and post-processing steps.
Additionally, the underlying models may evolve over time. Therefore, one should
not expect the performance of user-facing products to exactly match the results
reported in this report.