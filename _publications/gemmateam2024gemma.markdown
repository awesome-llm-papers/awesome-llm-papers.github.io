---
layout: publication
title: 'Gemma 2: Improving Open Language Models At A Practical Size'
authors: "Gemma Team, Morgane Riviere, Shreya Pathak, Pier Giuseppe Sessa, Cassidy\
  \ Hardin, Surya Bhupatiraju, L\xE9onard Hussenot, Thomas Mesnard, Bobak Shahriari,\
  \ Alexandre Ram\xE9, Johan Ferret, Peter Liu, Pouya Tafti, Abe Friesen, Michelle\
  \ Casbon, Sabela Ramos, Ravin Kumar, Charline Le Lan, Sammy Jerome, Anton Tsitsulin,\
  \ Nino Vieillard, Piotr Stanczyk, Sertan Girgin, Nikola Momchev, Matt Hoffman, Shantanu\
  \ Thakoor, Jean-bastien Grill, Behnam Neyshabur, Olivier Bachem, Alanna Walton,\
  \ Aliaksei Severyn, Alicia Parrish, Aliya Ahmad, Allen Hutchison, Alvin Abdagic,\
  \ Amanda Carl, Amy Shen, Andy Brock, Andy Coenen, Anthony Laforge, Antonia Paterson,\
  \ Ben Bastian, Bilal Piot, Bo Wu, Brandon Royal, Charlie Chen, Chintu Kumar, Chris\
  \ Perry, Chris Welty, Christopher A. Choquette-choo, Danila Sinopalnikov, David\
  \ Weinberger, Dimple Vijaykumar, Dominika Rogozi\u0144ska, Dustin Herbison, Elisa\
  \ Bandy, Emma Wang, Eric Noland, Erica Moreira, Evan Senter, Evgenii Eltyshev, Francesco\
  \ Visin, Gabriel Rasskin, Gary Wei, Glenn Cameron, Gus Martins, Hadi Hashemi, Hanna\
  \ Klimczak-pluci\u0144ska, Harleen Batra, Harsh Dhand, Ivan Nardini, Jacinda Mein,\
  \ Jack Zhou, James Svensson, Jeff Stanway, Jetha Chan, Jin Peng Zhou, Joana Carrasqueira,\
  \ Joana Iljazi, Jocelyn Becker, Joe Fernandez, Joost van Amersfoort, Josh Gordon,\
  \ Josh Lipschultz, Josh Newlan, Ju-yeong Ji, Kareem Mohamed, Kartikeya Badola, Kat\
  \ Black, Katie Millican, Keelin Mcdonell, Kelvin Nguyen, Kiranbir Sodhia, Kish Greene,\
  \ Lars Lowe Sjoesund, Lauren Usui, Laurent Sifre, Lena Heuermann, Leticia Lago,\
  \ Lilly Mcnealus, Livio Baldini Soares, Logan Kilpatrick, Lucas Dixon, Luciano Martins,\
  \ Machel Reid, Manvinder Singh, Mark Iverson, Martin G\xF6rner, Mat Velloso, Mateo\
  \ Wirth, Matt Davidow, Matt Miller, Matthew Rahtz, Matthew Watson, Meg Risdal, Mehran\
  \ Kazemi, Michael Moynihan, Ming Zhang, Minsuk Kahng, Minwoo Park, Mofi Rahman,\
  \ Mohit Khatwani, Natalie Dao, Nenshad Bardoliwalla, Nesh Devanathan, Neta Dumai,\
  \ Nilay Chauhan, Oscar Wahltinez, Pankil Botarda, Parker Barnes, Paul Barham, Paul\
  \ Michel, Pengchong Jin, Petko Georgiev, Phil Culliton, Pradeep Kuppala, Ramona\
  \ Comanescu, Ramona Merhej, Reena Jana, Reza Ardeshir Rokni, Rishabh Agarwal, Ryan\
  \ Mullins, Samaneh Saadat, Sara Mc Carthy, Sarah Cogan, Sarah Perrin, S\xE9bastien\
  \ M. R. Arnold, Sebastian Krause, Shengyang Dai, Shruti Garg, Shruti Sheth, Sue\
  \ Ronstrom, Susan Chan, Timothy Jordan, Ting Yu, Tom Eccles, Tom Hennigan, Tomas\
  \ Kocisky, Tulsee Doshi, Vihan Jain, Vikas Yadav, Vilobh Meshram, Vishal Dharmadhikari,\
  \ Warren Barkley, Wei Wei, Wenming Ye, Woohyun Han, Woosuk Kwon, Xiang Xu, Zhe Shen,\
  \ Zhitao Gong, Zichuan Wei, Victor Cotruta, Phoebe Kirk, Anand Rao, Minh Giang,\
  \ Ludovic Peran, Tris Warkentin, Eli Collins, Joelle Barral, Zoubin Ghahramani,\
  \ Raia Hadsell, D. Sculley, Jeanine Banks, Anca Dragan, Slav Petrov, Oriol Vinyals,\
  \ Jeff Dean, Demis Hassabis, Koray Kavukcuoglu, Clement Farabet, Elena Buchatskaya,\
  \ Sebastian Borgeaud, Noah Fiedel, Armand Joulin, Kathleen Kenealy, Robert Dadashi,\
  \ Alek Andreev"
conference: Arxiv
year: 2024
bibkey: gemmateam2024gemma
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.00118'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Team et al.
---
In this work, we introduce Gemma 2, a new addition to the Gemma family of
lightweight, state-of-the-art open models, ranging in scale from 2 billion to
27 billion parameters. In this new version, we apply several known technical
modifications to the Transformer architecture, such as interleaving
local-global attentions (Beltagy et al., 2020a) and group-query attention
(Ainslie et al., 2023). We also train the 2B and 9B models with knowledge
distillation (Hinton et al., 2015) instead of next token prediction. The
resulting models deliver the best performance for their size, and even offer
competitive alternatives to models that are 2-3 times bigger. We release all
our models to the community.