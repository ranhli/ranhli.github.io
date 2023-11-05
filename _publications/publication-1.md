---
title: "Learned Smartphone ISP on Mobile GPUs, Mobile AI & AIM 2022 Challenge Report"
collection: publications
permalink: /publication/mobile-ai-challenge-report
excerpt: "• Collaborated with graduate students on image restoration. Presented model to ETH Zurich professor Andrey Ignatov.            
• Earned highest metric score among over 100 teams. Publication available [here](https://arxiv.org/abs/2211.03885)."
date: 2022-10-01
venue: ""
# paperurl: "https://arxiv.org/abs/2211.03885"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

The role of mobile cameras increased dramatically over the past few years, leading to more and more research in automatic image quality enhancement and RAW photo processing. In this Mobile AI challenge, the target was to develop an efficient end-to-end AI-based image signal processing (ISP) pipeline replacing the standard mobile ISPs that can run on modern smartphone GPUs using TensorFlow Lite. The participants were provided with a large-scale Fujifilm UltraISP dataset consisting of thousands of paired photos captured with a normal mobile camera sensor and a professional 102MP medium-format FujiFilm GFX100 camera. The runtime of the resulting models was evaluated on the Snapdragon's 8 Gen 1 GPU that provides excellent acceleration results for the majority of common deep learning ops. The proposed solutions are compatible with all recent mobile GPUs, being able to process Full HD photos in less than 20-50 milliseconds while achieving high fidelity results. A detailed description of all models developed in this challenge is provided in this paper.
