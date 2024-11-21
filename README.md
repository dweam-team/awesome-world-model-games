# Awesome World Model Games [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

World model games are awesome!

Here we collect papers, open-source projects, and applications of such interactive video models.

Click the badges below the heading to visit the project's relevant links.

The badge ![X FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-X%20FPS-green) indicates an estimate of the frames per second of the model when run on an NVIDIA RTX 4090 GPU at reasonable inference settings. Anything below 1 FPS will be highlighted in red ![<1 FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-<1%20FPS-red). In case of ![??? FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-%3F%3F%3F%20FPS-yellow), model performance on an RTX 4090 has not yet been reported. 

Contributions are very welcome!

## Contents

- [DIAMOND](#diamond)
- [Oasis](#oasis)
- [Lucid](#lucid-v1)
- [Other Games](#other)
- [Papers](#papers)

## DIAMOND
[![Homepage](https://img.shields.io/badge/homepage-gray)](https://diamond-wm.github.io/)
[![arXiv](https://img.shields.io/badge/arXiv-red)](https://arxiv.org/abs/2405.12399)
[![Discord](https://img.shields.io/badge/discord-purple)](https://discord.gg/74vha5RWPg)

Open-source training and inference, initially launched with 26 atari games and CS:GO.

### Atari Games
![??? FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-%3F%3F%3F%20FPS-yellow)
[![Open Source](https://img.shields.io/badge/open%20source-blue)](https://github.com/eloialonso/diamond) 

100M models of 26 Atari games.

<img src="https://github.com/user-attachments/assets/eb6b72eb-73df-4178-8a3d-cdad80ff9152" width="500"/>

### CS:GO 
![>10 FPS on RTX 4090](https://img.shields.io/badge/RTX%204090->10%20FPS-green)
[![Open Source](https://img.shields.io/badge/open%20source-blue)](https://github.com/eloialonso/diamond/tree/csgo)

<img src="https://github.com/user-attachments/assets/dcbdd523-ca22-46a9-bb7d-bcc52080fe00" width="500"/>

### Mario Kart 64 
![??? FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-%3F%3F%3F%20FPS-yellow)
[![Open Source](https://img.shields.io/badge/open%20source-blue)](https://github.com/Dere-Wah/AI-MarioKart64)
[![Demo](https://img.shields.io/badge/demo-green)](https://www.youtube.com/watch?v=C1Xrxa4qNk4)
[![Blog](https://img.shields.io/badge/blog-orange)](https://derewah.dev/projects/ai-mariokart)

![mariokart](https://github.com/user-attachments/assets/0dbdfeec-4d4d-4f70-8ba1-3e728138fd0a)

## Oasis

### Minecraft
![<1 FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-%3C1%20FPS-red)
[![Open Source](https://img.shields.io/badge/open%20source-blue)](https://github.com/etched-ai/open-oasis)
[![Homepage](https://img.shields.io/badge/homepage-gray)](https://www.decart.ai/)
[![Demo](https://img.shields.io/badge/demo-green)](https://oasis.decart.ai/)
[![Blog](https://img.shields.io/badge/blog-orange)](https://www.decart.ai/articles/oasis-interactive-ai-video-game-model)

A 500M model and inference code are open-source.

<img src="https://cdn.prod.website-files.com/671a36395e56dbd229da0e0e/6723b0a589d2f810325afdcb_4.webp" width="500"/>

## Lucid 

### Minecraft
![20 FPS on RTX 4090](https://img.shields.io/badge/RTX%204090-20%20FPS-green)
[![Open Source](https://img.shields.io/badge/open%20source-blue)](https://github.com/SonicCodes/lucid-v1)
[![Demo](https://img.shields.io/badge/demo-green)](https://lucidv1-demo.vercel.app/)
[![Blog](https://img.shields.io/badge/blog-orange)](https://ramimo.substack.com/p/lucid-v1-a-world-model-that-does)

One size of the model and inference code are open-source.

<img src="https://github.com/user-attachments/assets/e08a2fdd-232d-4b9c-8f1c-8f9b9f1babe7" width="500"/>

## Other Games

### Matrix
[![Homepage](https://img.shields.io/badge/homepage-gray)](https://thematrix1999.github.io/)

2.7B model trained on data from Forza Horizon 5 and Cyberpunk 2077 as well as real-world footage.

<img src="https://github.com/user-attachments/assets/c3fbae6d-1393-4fd9-97d8-db61bed139e0" width="500"/>

### GameNGen
[![Homepage](https://img.shields.io/badge/homepage-gray)](https://gamengen.github.io/)
[![arXiv](https://img.shields.io/badge/arXiv-red)](https://arxiv.org/abs/2408.14837)

It runs Doom! The grandfather paper of the field.

[![Watch the video](https://img.youtube.com/vi/O3616ZFGpqw/0.jpg)](https://www.youtube.com/watch?v=O3616ZFGpqw)

### Genie
[![Homepage](https://img.shields.io/badge/homepage-gray)](https://sites.google.com/view/genie-2024/)
[![arXiv](https://img.shields.io/badge/arXiv-red)](https://arxiv.org/abs/2402.15391)

Seminal paper generalising world models to different games (and pictures!), focused on 2D platformers.

<img src="https://github.com/user-attachments/assets/3b476676-224f-4800-bc39-56dbd84944cb" width="500"/>

### Pokemon Overworld
[![Demo](https://img.shields.io/badge/demo-yellow)](https://madebyoll.in/posts/game_emulation_via_dnn/demo)
[![Blog](https://img.shields.io/badge/blog-orange)](https://madebyoll.in/posts/game_emulation_via_dnn/)

An early model trained on a 4th Generation Pokemon game.

![Pokemon](https://madebyoll.in/posts/game_emulation_via_dnn/neural_notwork_3.gif)

## Papers

Game Papers:
- [The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control](https://thematrix1999.github.io/article/the_matrix.pdf) - Matrix Paper (Nov 2024).
- [Diffusion for World Modeling: Visual Details Matter in Atari](https://arxiv.org/pdf/2405.12399) - Diamond Paper (Oct 2024).
- [Diffusion Models are Real-time Game Engines](https://arxiv.org/pdf/2408.14837) - GameNGen Paper (Aug 2024).
- [Genie: Generative Interactive Environments](https://arxiv.org/pdf/2402.15391) - Genie Paper (Feb 2024).

