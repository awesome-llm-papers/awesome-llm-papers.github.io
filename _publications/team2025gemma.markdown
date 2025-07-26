---
layout: publication
title: Gemma 3 Technical Report
authors: "Gemma Team, Aishwarya Kamath, Johan Ferret, Shreya Pathak, Nino Vieillard,\
  \ Ramona Merhej, Sarah Perrin, Tatiana Matejovicova, Alexandre Ram\xE9, Morgane\
  \ Rivi\xE8re, Louis Rouillard, Thomas Mesnard, Geoffrey Cideron, Jean-bastien Grill,\
  \ Sabela Ramos, Edouard Yvinec, Michelle Casbon, Etienne Pot, Ivo Penchev, Ga\xEB\
  l Liu, Francesco Visin, Kathleen Kenealy, Lucas Beyer, Xiaohai Zhai, Anton Tsitsulin,\
  \ Robert Busa-fekete, Alex Feng, Noveen Sachdeva, Benjamin Coleman, Yi Gao, Basil\
  \ Mustafa, Iain Barr, Emilio Parisotto, David Tian, Matan Eyal, Colin Cherry, Jan-thorsten\
  \ Peter, Danila Sinopalnikov, Surya Bhupatiraju, Rishabh Agarwal, Mehran Kazemi,\
  \ Dan Malkin, Ravin Kumar, David Vilar, Idan Brusilovsky, Jiaming Luo, Andreas Steiner,\
  \ Abe Friesen, Abhanshu Sharma, Abheesht Sharma, Adi Mayrav Gilady, Adrian Goedeckemeyer,\
  \ Alaa Saade, Alex Feng, Alexander Kolesnikov, Alexei Bendebury, Alvin Abdagic,\
  \ Amit Vadi, Andr\xE1s Gy\xF6rgy, Andr\xE9 Susano Pinto, Anil Das, Ankur Bapna,\
  \ Antoine Miech, Antoine Yang, Antonia Paterson, Ashish Shenoy, Ayan Chakrabarti,\
  \ Bilal Piot, Bo Wu, Bobak Shahriari, Bryce Petrini, Charlie Chen, Charline Le Lan,\
  \ Christopher A. Choquette-choo, Cj Carey, Cormac Brick, Daniel Deutsch, Danielle\
  \ Eisenbud, Dee Cattle, Derek Cheng, Dimitris Paparas, Divyashree Shivakumar Sreepathihalli,\
  \ Doug Reid, Dustin Tran, Dustin Zelle, Eric Noland, Erwin Huizenga, Eugene Kharitonov,\
  \ Frederick Liu, Gagik Amirkhanyan, Glenn Cameron, Hadi Hashemi, Hanna Klimczak-pluci\u0144\
  ska, Harman Singh, Harsh Mehta, Harshal Tushar Lehri, Hussein Hazimeh, Ian Ballantyne,\
  \ Idan Szpektor, Ivan Nardini, Jean Pouget-abadie, Jetha Chan, Joe Stanton, John\
  \ Wieting, Jonathan Lai, Jordi Orbay, Joseph Fernandez, Josh Newlan, Ju-yeong Ji,\
  \ Jyotinder Singh, Kat Black, Kathy Yu, Kevin Hui, Kiran Vodrahalli, Klaus Greff,\
  \ Linhai Qiu, Marcella Valentine, Marina Coelho, Marvin Ritter, Matt Hoffman, Matthew\
  \ Watson, Mayank Chaturvedi, Michael Moynihan, Min Ma, Nabila Babar, Natasha Noy,\
  \ Nathan Byrd, Nick Roy, Nikola Momchev, Nilay Chauhan, Noveen Sachdeva, Oskar Bunyan,\
  \ Pankil Botarda, Paul Caron, Paul Kishan Rubenstein, Phil Culliton, Philipp Schmid,\
  \ Pier Giuseppe Sessa, Pingmei Xu, Piotr Stanczyk, Pouya Tafti, Rakesh Shivanna,\
  \ Renjie Wu, Renke Pan, Reza Rokni, Rob Willoughby, Rohith Vallu, Ryan Mullins,\
  \ Sammy Jerome, Sara Smoot, Sertan Girgin, Shariq Iqbal, Shashir Reddy, Shruti Sheth,\
  \ Siim P\xF5der, Sijal Bhatnagar, Sindhu Raghuram Panyam, Sivan Eiger, Susan Zhang,\
  \ Tianqi Liu, Trevor Yacovone, Tyler Liechty, Uday Kalra, Utku Evci, Vedant Misra,\
  \ Vincent Roseberry, Vlad Feinberg, Vlad Kolesnikov, Woohyun Han, Woosuk Kwon, Xi\
  \ Chen, Yinlam Chow, Yuvein Zhu, Zichuan Wei, Zoltan Egyed, Victor Cotruta, Minh\
  \ Giang, Phoebe Kirk, Anand Rao, Kat Black, Nabila Babar, Jessica Lo, Erica Moreira,\
  \ Luiz Gustavo Martins, Omar Sanseviero, Lucas Gonzalez, Zach Gleicher, Tris Warkentin,\
  \ Vahab Mirrokni, Evan Senter, Eli Collins, Joelle Barral, Zoubin Ghahramani, Raia\
  \ Hadsell, Yossi Matias, D. Sculley, Slav Petrov, Noah Fiedel, Noam Shazeer, Oriol\
  \ Vinyals, Jeff Dean, Demis Hassabis, Koray Kavukcuoglu, Clement Farabet, Elena\
  \ Buchatskaya, Jean-baptiste Alayrac, Rohan Anil, Dmitry, Lepikhin, Sebastian Borgeaud,\
  \ Olivier Bachem, Armand Joulin, Alek Andreev, Cassidy Hardin, Robert Dadashi, L\xE9\
  onard Hussenot"
conference: No Venue
year: 2025
bibkey: team2025gemma
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.19786'}]
tags: ["Efficiency", "Memory & Context", "Model Architecture", "Training Techniques"]
short_authors: Team et al.
---
We introduce Gemma 3, a multimodal addition to the Gemma family of lightweight open models, ranging in scale from 1 to 27 billion parameters. This version introduces vision understanding abilities, a wider coverage of languages and longer context - at least 128K tokens. We also change the architecture of the model to reduce the KV-cache memory that tends to explode with long context. This is achieved by increasing the ratio of local to global attention layers, and keeping the span on local attention short. The Gemma 3 models are trained with distillation and achieve superior performance to Gemma 2 for both pre-trained and instruction finetuned versions. In particular, our novel post-training recipe significantly improves the math, chat, instruction-following and multilingual abilities, making Gemma3-4B-IT competitive with Gemma2-27B-IT and Gemma3-27B-IT comparable to Gemini-1.5-Pro across benchmarks. We release all our models to the community.

https://huggingface.co/discussions/paper/67e5267638e4d1444c8bbaa3