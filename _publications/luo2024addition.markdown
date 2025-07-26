---
layout: publication
title: Addition Is All You Need For Energy-efficient Language Models
authors: Hongyin Luo, Wei Sun
conference: No Venue
year: 2024
bibkey: luo2024addition
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.00907'}]
tags: ["Model Architecture"]
short_authors: Hongyin Luo, Wei Sun
---
Large neural networks spend most computation on floating point tensor multiplications. In this work, we find that a floating point multiplier can be approximated by one integer adder with high precision. We propose the linear-complexity multiplication L-Mul algorithm that approximates floating point number multiplication with integer addition operations. The new algorithm costs significantly less computation resource than 8-bit floating point multiplication but achieves higher precision. Compared to 8-bit floating point multiplications, the proposed method achieves higher precision but consumes significantly less bit-level computation. Since multiplying floating point numbers requires substantially higher energy compared to integer addition operations, applying the L-Mul operation in tensor processing hardware can potentially reduce 95% energy cost by element-wise floating point tensor multiplications and 80% energy cost of dot products. We calculated the theoretical error expectation of L-Mul, and evaluated the algorithm on a wide range of textual, visual, and symbolic tasks, including natural language understanding, structural reasoning, mathematics, and commonsense question answering. Our numerical analysis experiments agree with the theoretical error estimation, which indicates that L-Mul with 4-bit mantissa achieves comparable precision as float8_e4m3 multiplications, and L-Mul with 3-bit mantissa outperforms float8_e5m2. Evaluation results on popular benchmarks show that directly applying L-Mul to the attention mechanism is almost lossless. We further show that replacing all floating point multiplications with 3-bit mantissa L-Mul in a transformer model achieves equivalent precision as using float8_e4m3 as accumulation precision in both fine-tuning and inference.

https://huggingface.co/discussions/paper/66fc9efb6d3e4a039730c6c9