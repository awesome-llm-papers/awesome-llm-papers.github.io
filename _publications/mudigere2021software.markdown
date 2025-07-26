---
layout: publication
title: Software-hardware Co-design For Fast And Scalable Training Of Deep Learning
  Recommendation Models
authors: Dheevatsa Mudigere, Yuchen Hao, Jianyu Huang, Zhihao Jia, Andrew Tulloch,
  Srinivas Sridharan, Xing Liu, Mustafa Ozdal, Jade Nie, Jongsoo Park, Liang Luo,
  Jie Amy Yang, Leon Gao, Dmytro Ivchenko, Aarti Basant, Yuxi Hu, Jiyan Yang, Ehsan
  K. Ardestani, Xiaodong Wang, Rakesh Komuravelli, Ching-hsiang Chu, Serhat Yilmaz,
  Huayu Li, Jiyuan Qian, Zhuobo Feng, Yinbin Ma, Junjie Yang, Ellie Wen, Hong Li,
  Lin Yang, Chonglin Sun, Whitney Zhao, Dimitry Melts, Krishna Dhulipala, Kr Kishore,
  Tyler Graf, Assaf Eisenman, Kiran Kumar Matam, Adi Gangidi, Guoqiang Jerry Chen,
  Manoj Krishnan, Avinash Nayak, Krishnakumar Nair, Bharath Muthiah, Mahmoud Khorashadi,
  Pallab Bhattacharya, Petr Lapukhov, Maxim Naumov, Ajit Mathews, Lin Qiao, Mikhail
  Smelyanskiy, Bill Jia, Vijay Rao
conference: Proceedings of the 49th Annual International Symposium on Computer Architecture
year: 2022
bibkey: mudigere2021software
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.05158'}]
tags: ["Tools", "Training Techniques"]
short_authors: Mudigere et al.
---
Deep learning recommendation models (DLRMs) are used across many
business-critical services at Facebook and are the single largest AI
application in terms of infrastructure demand in its data-centers. In this
paper we discuss the SW/HW co-designed solution for high-performance
distributed training of large-scale DLRMs. We introduce a high-performance
scalable software stack based on PyTorch and pair it with the new evolution of
Zion platform, namely ZionEX. We demonstrate the capability to train very large
DLRMs with up to 12 Trillion parameters and show that we can attain 40X speedup
in terms of time to solution over previous systems. We achieve this by (i)
designing the ZionEX platform with dedicated scale-out network, provisioned
with high bandwidth, optimal topology and efficient transport (ii) implementing
an optimized PyTorch-based training stack supporting both model and data
parallelism (iii) developing sharding algorithms capable of hierarchical
partitioning of the embedding tables along row, column dimensions and load
balancing them across multiple workers; (iv) adding high-performance core
operators while retaining flexibility to support optimizers with fully
deterministic updates (v) leveraging reduced precision communications,
multi-level memory hierarchy (HBM+DDR+SSD) and pipelining. Furthermore, we
develop and briefly comment on distributed data ingestion and other supporting
services that are required for the robust and efficient end-to-end training in
production environments.