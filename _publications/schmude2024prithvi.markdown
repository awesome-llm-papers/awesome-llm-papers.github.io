---
layout: publication
title: 'Prithvi Wxc: Foundation Model For Weather And Climate'
authors: Johannes Schmude, Sujit Roy, Will Trojak, Johannes Jakubik, Daniel Salles
  Civitarese, Shraddha Singh, Julian Kuehnert, Kumar Ankur, Aman Gupta, Christopher
  E Phillips, Romeo Kienzler, Daniela Szwarcman, Vishal Gaur, Rajat Shinde, Rohit
  Lal, Arlindo da Silva, Jorge Luis Guevara Diaz, Anne Jones, Simon Pfreundschuh,
  Amy Lin, Aditi Sheshadri, Udaysankar Nair, Valentine Anantharaj, Hendrik Hamann,
  Campbell Watson, Manil Maskey, Tsengdar J Lee, Juan Bernabe Moreno, Rahul Ramachandran
conference: No Venue
year: 2024
bibkey: schmude2024prithvi
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66f0c7e60c00b14702737434'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.13598'}]
tags: ["Applications", "Time Series"]
short_authors: Schmude et al.
---
Triggered by the realization that AI emulators can rival the performance of traditional numerical weather prediction models running on HPC systems, there is now an increasing number of large AI models that address use cases such as forecasting, downscaling, or nowcasting. While the parallel developments in the AI literature focus on foundation models -- models that can be effectively tuned to address multiple, different use cases -- the developments on the weather and climate side largely focus on single-use cases with particular emphasis on mid-range forecasting. We close this gap by introducing Prithvi WxC, a 2.3 billion parameter foundation model developed using 160 variables from the Modern-Era Retrospective Analysis for Research and Applications, Version 2 (MERRA-2). Prithvi WxC employs an encoder-decoder-based architecture, incorporating concepts from various recent transformer models to effectively capture both regional and global dependencies in the input data. The model has been designed to accommodate large token counts to model weather phenomena in different topologies at fine resolutions. Furthermore, it is trained with a mixed objective that combines the paradigms of masked reconstruction with forecasting. We test the model on a set of challenging downstream tasks namely: Autoregressive rollout forecasting, Downscaling, Gravity wave flux parameterization, and Extreme events estimation. The pretrained model with 2.3 billion parameters, along with the associated fine-tuning workflows, has been publicly released as an open-source contribution via Hugging Face.

https://huggingface.co/discussions/paper/66f0c7e60c00b14702737434