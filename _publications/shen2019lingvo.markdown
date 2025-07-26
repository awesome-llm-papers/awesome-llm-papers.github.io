---
layout: publication
title: 'Lingvo: A Modular And Scalable Framework For Sequence-to-sequence Modeling'
authors: "Jonathan Shen, Patrick Nguyen, Yonghui Wu, Zhifeng Chen, Mia X. Chen, Ye\
  \ Jia, Anjuli Kannan, Tara Sainath, Yuan Cao, Chung-cheng Chiu, Yanzhang He, Jan\
  \ Chorowski, Smit Hinsu, Stella Laurenzo, James Qin, Orhan Firat, Wolfgang Macherey,\
  \ Suyog Gupta, Ankur Bapna, Shuyuan Zhang, Ruoming Pang, Ron J. Weiss, Rohit Prabhavalkar,\
  \ Qiao Liang, Benoit Jacob, Bowen Liang, Hyoukjoong Lee, Ciprian Chelba, S\xE9bastien\
  \ Jean, Bo Li, Melvin Johnson, Rohan Anil, Rajat Tibrewal, Xiaobing Liu, Akiko Eriguchi,\
  \ Navdeep Jaitly, Naveen Ari, Colin Cherry, Parisa Haghani, Otavio Good, Youlong\
  \ Cheng, Raziel Alvarez, Isaac Caswell, Wei-ning Hsu, Zongheng Yang, Kuan-chieh\
  \ Wang, Ekaterina Gonina, Katrin Tomanek, Ben Vanik, Zelin Wu, Llion Jones, Mike\
  \ Schuster, Yanping Huang, Dehao Chen, Kazuki Irie, George Foster, John Richardson,\
  \ Klaus Macherey, Antoine Bruguier, Heiga Zen, Colin Raffel, Shankar Kumar, Kanishka\
  \ Rao, David Rybach, Matthew Murray, Vijayaditya Peddinti, Maxim Krikun, Michiel\
  \ A. U. Bacchiani, Thomas B. Jablin, Rob Suderman, Ian Williams, Benjamin Lee, Deepti\
  \ Bhatia, Justin Carlson, Semih Yavuz, Yu Zhang, Ian Mcgraw, Max Galkin, Qi Ge,\
  \ Golan Pundak, Chad Whipkey, Todd Wang, Uri Alon, Dmitry Lepikhin, Ye Tian, Sara\
  \ Sabour, William Chan, Shubham Toshniwal, Baohua Liao, Michael Nirschl, Pat Rondon"
conference: Arxiv
year: 2019
bibkey: shen2019lingvo
citations: 202
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.08295'}]
tags: ["Tools", "Training Techniques"]
short_authors: Shen et al.
---
Lingvo is a Tensorflow framework offering a complete solution for
collaborative deep learning research, with a particular focus towards
sequence-to-sequence models. Lingvo models are composed of modular building
blocks that are flexible and easily extensible, and experiment configurations
are centralized and highly customizable. Distributed training and quantized
inference are supported directly within the framework, and it contains existing
implementations of a large number of utilities, helper functions, and the
newest research ideas. Lingvo has been used in collaboration by dozens of
researchers in more than 20 papers over the last two years. This document
outlines the underlying design of Lingvo and serves as an introduction to the
various pieces of the framework, while also offering examples of advanced
features that showcase the capabilities of the framework.