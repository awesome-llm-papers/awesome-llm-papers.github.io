---
layout: publication
title: Openai O1 System Card
authors: "Openai, Aaron Jaech, Adam Kalai, Adam Lerer, Adam Richardson, Ahmed El-kishky,\
  \ Aiden Low, Alec Helyar, Aleksander Madry, Alex Beutel, Alex Carney, Alex Iftimie,\
  \ Alex Karpenko, Alex Tachard Passos, Alexander Neitz, Alexander Prokofiev, Alexander\
  \ Wei, Allison Tam, Ally Bennett, Ananya Kumar, Andre Saraiva, Andrea Vallone, Andrew\
  \ Duberstein, Andrew Kondrich, Andrey Mishchenko, Andy Applebaum, Angela Jiang,\
  \ Ashvin Nair, Barret Zoph, Behrooz Ghorbani, Ben Rossen, Benjamin Sokolowsky, Boaz\
  \ Barak, Bob Mcgrew, Borys Minaiev, Botao Hao, Bowen Baker, Brandon Houghton, Brandon\
  \ Mckinzie, Brydon Eastman, Camillo Lugaresi, Cary Bassin, Cary Hudson, Chak Ming\
  \ Li, Charles de Bourcy, Chelsea Voss, Chen Shen, Chong Zhang, Chris Koch, Chris\
  \ Orsinger, Christopher Hesse, Claudia Fischer, Clive Chan, Dan Roberts, Daniel\
  \ Kappler, Daniel Levy, Daniel Selsam, David Dohan, David Farhi, David Mely, David\
  \ Robinson, Dimitris Tsipras, Doug Li, Dragos Oprica, Eben Freeman, Eddie Zhang,\
  \ Edmund Wong, Elizabeth Proehl, Enoch Cheung, Eric Mitchell, Eric Wallace, Erik\
  \ Ritter, Evan Mays, Fan Wang, Felipe Petroski Such, Filippo Raso, Florencia Leoni,\
  \ Foivos Tsimpourlas, Francis Song, Fred von Lohmann, Freddie Sulit, Geoff Salmon,\
  \ Giambattista Parascandolo, Gildas Chabot, Grace Zhao, Greg Brockman, Guillaume\
  \ Leclerc, Hadi Salman, Haiming Bao, Hao Sheng, Hart Andrin, Hessam Bagherinezhad,\
  \ Hongyu Ren, Hunter Lightman, Hyung Won Chung, Ian Kivlichan, Ian O'connell, Ian\
  \ Osband, Ignasi Clavera Gilaberte, Ilge Akkaya, Ilya Kostrikov, Ilya Sutskever,\
  \ Irina Kofman, Jakub Pachocki, James Lennon, Jason Wei, Jean Harb, Jerry Twore,\
  \ Jiacheng Feng, Jiahui Yu, Jiayi Weng, Jie Tang, Jieqi Yu, Joaquin Qui\xF1onero\
  \ Candela, Joe Palermo, Joel Parish, Johannes Heidecke, John Hallman, John Rizzo,\
  \ Jonathan Gordon, Jonathan Uesato, Jonathan Uesato, Jonathan Ward, Joost Huizinga,\
  \ Julie Wang, Kai Chen, Kai Xiao, Karan Singhal, Karina Nguyen, Karl Cobbe, Katy\
  \ Shi, Kayla Wood, Kendra Rimbach, Keren Gu-lemberg, Keren Gulemberg, Kevin Liu,\
  \ Kevin Lu, Kevin Stone, Kevin Yu, Lama Ahmad, Lauren Yang, Leo Liu, Leon Maksin,\
  \ Leyton Ho, Liam Fedus, Lilian Weng, Linden Li, Lindsay Mccallum, Lindsey Held,\
  \ Lorenz Kuhn, Lukas Kondraciuk, Lukasz Kaiser, Luke Metz, Madelaine Boyd, Maja\
  \ Trebacz, Manas Joglekar, Mark Chen, Marko Tintor, Mason Meyer, Matt Jones, Matt\
  \ Kaufer, Max Schwarzer, Meghan Shah, Mehmet Yatbaz, Melody Guan, Mengyuan Xu, Mengyuan\
  \ Yan, Mia Glaese, Mianna Chen, Mianna Chen, Michael Lampe, Michael Malek, Michele\
  \ Wang, Michelle Fradin, Mike Mcclay, Mikhail Pavlov, Miles Wang, Mingxuan Wang,\
  \ Mira Murati, Mo Bavarian, Mostafa Rohaninejad, Nat Mcaleese, Neil Chowdhury, Neil\
  \ Chowdhury, Nick Ryder, Nikolas Tezak, Noam Brown, Ofir Nachum, Oleg Boiko, Oleg\
  \ Murk, Olivia Watkins, Patrick Chao, Paul Ashbourne, Pavel Izmailov, Peter Zhokhov,\
  \ Rachel Dias, Rahul Arora, Randall Lin, Rapha Gontijo Lopes, Raz Gaon, Reah Miyara,\
  \ Reimar Leike, Renny Hwang, Rhythm Garg, Robin Brown, Roshan James, Rui Shu, Ryan\
  \ Cheu, Ryan Greene, Saachi Jain, Sam Altman, Sam Toizer, Sam Toyer, Samuel Miserendino,\
  \ Sandhini Agarwal, Santiago Hernandez, Sasha Baker, Scott Mckinney, Scottie Yan,\
  \ Shengjia Zhao, Shengli Hu, Shibani Santurkar, Shraman Ray Chaudhuri, Shuyuan Zhang,\
  \ Siyuan Fu, Spencer Papay, Steph Lin, Suchir Balaji, Suvansh Sanjeev, Szymon Sidor,\
  \ Tal Broda, Aidan Clark, Tao Wang, Taylor Gordon, Ted Sanders, Tejal Patwardhan,\
  \ Thibault Sottiaux, Thomas Degry, Thomas Dimson, Tianhao Zheng, Timur Garipov,\
  \ Tom Stasi, Trapit Bansal, Trevor Creech, Troy Peterson, Tyna Eloundou, Valerie\
  \ Qi, Vineet Kosaraju, Vinnie Monaco, Vitchyr Pong, Vlad Fomenko, Weiyi Zheng, Wenda\
  \ Zhou, Wes Mccabe, Wojciech Zaremba, Yann Dubois, Yinghai Lu, Yining Chen, Young\
  \ Cha, Yu Bai, Yuchen He, Yuchen Zhang, Yunyun Wang, Zheng Shao, Zhuohan Li"
conference: No Venue
year: 2024
bibkey: 2024openai
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/676a5f1427c8341daf37c9c1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.16720'}]
tags: ["Ethics & Fairness", "Reinforcement Learning", "Security", "Tools", "Training Techniques"]
short_authors: Openai et al.
---
The o1 model series is trained with large-scale reinforcement learning to reason using chain of thought. These advanced reasoning capabilities provide new avenues for improving the safety and robustness of our models. In particular, our models can reason about our safety policies in context when responding to potentially unsafe prompts, through deliberative alignment. This leads to state-of-the-art performance on certain benchmarks for risks such as generating illicit advice, choosing stereotyped responses, and succumbing to known jailbreaks. Training models to incorporate a chain of thought before answering has the potential to unlock substantial benefits, while also increasing potential risks that stem from heightened intelligence. Our results underscore the need for building robust alignment methods, extensively stress-testing their efficacy, and maintaining meticulous risk management protocols. This report outlines the safety work carried out for the OpenAI o1 and OpenAI o1-mini models, including safety evaluations, external red teaming, and Preparedness Framework evaluations.

https://huggingface.co/discussions/paper/676a5f1427c8341daf37c9c1