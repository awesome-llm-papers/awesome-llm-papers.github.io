---
layout: publication
title: 'Swiftedit: Lightning Fast Text-guided Image Editing Via One-step Diffusion'
authors: Trong-tung Nguyen, Quang Nguyen, Khoi Nguyen, Anh Tran, Cuong Pham
conference: No Venue
year: 2024
bibkey: nguyen2024swiftedit
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.04301'}]
tags: ["Applications", "Efficiency", "Has Code", "Tools"]
short_authors: Nguyen et al.
---
Recent advances in text-guided image editing enable users to perform image edits through simple text inputs, leveraging the extensive priors of multi-step diffusion-based text-to-image models. However, these methods often fall short of the speed demands required for real-world and on-device applications due to the costly multi-step inversion and sampling process involved. In response to this, we introduce SwiftEdit, a simple yet highly efficient editing tool that achieve instant text-guided image editing (in 0.23s). The advancement of SwiftEdit lies in its two novel contributions: a one-step inversion framework that enables one-step image reconstruction via inversion and a mask-guided editing technique with our proposed attention rescaling mechanism to perform localized image editing. Extensive experiments are provided to demonstrate the effectiveness and efficiency of SwiftEdit. In particular, SwiftEdit enables instant text-guided image editing, which is extremely faster than previous multi-step methods (at least 50 times faster) while maintain a competitive performance in editing results. Our project page is at: https://swift-edit.github.io/

https://huggingface.co/discussions/paper/67566093ae453181a53677d2