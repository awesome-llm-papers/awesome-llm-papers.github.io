---
layout: publication
title: 'Cinemaster: A 3d-aware And Controllable Framework For Cinematic Text-to-video
  Generation'
authors: Qinghe Wang, Yawen Luo, Xiaoyu Shi, Xu Jia, Huchuan Lu, Tianfan Xue, Xintao
  Wang, Pengfei Wan, di Zhang, Kun Gai
conference: No Venue
year: 2025
bibkey: wang2025cinemaster
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.08639'}]
tags: ["Has Code", "Tools"]
short_authors: Wang et al.
---
In this work, we present CineMaster, a novel framework for 3D-aware and controllable text-to-video generation. Our goal is to empower users with comparable controllability as professional film directors: precise placement of objects within the scene, flexible manipulation of both objects and camera in 3D space, and intuitive layout control over the rendered frames. To achieve this, CineMaster operates in two stages. In the first stage, we design an interactive workflow that allows users to intuitively construct 3D-aware conditional signals by positioning object bounding boxes and defining camera movements within the 3D space. In the second stage, these control signals--comprising rendered depth maps, camera trajectories and object class labels--serve as the guidance for a text-to-video diffusion model, ensuring to generate the user-intended video content. Furthermore, to overcome the scarcity of in-the-wild datasets with 3D object motion and camera pose annotations, we carefully establish an automated data annotation pipeline that extracts 3D bounding boxes and camera trajectories from large-scale video data. Extensive qualitative and quantitative experiments demonstrate that CineMaster significantly outperforms existing methods and implements prominent 3D-aware text-to-video generation. Project page: https://cinemaster-dev.github.io/.

https://huggingface.co/discussions/paper/67ad5f26cad644864b4361cf