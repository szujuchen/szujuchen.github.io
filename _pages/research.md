---
layout: archive
title: ""
permalink: /research/
author_profile: true
pageTitle: "Szu-Ju Chen"
---

# Research Experiences 

## MACHI Program in DATA Lab — Rice University, United States  
Visiting Student | Feb. 2025 – Mar. 2025 | Advisor: Dr. Xia Ben Hu

I worked with my mentor, Yu-Neng Chuang, on a new project that focused on improving the efficiency of routing frameworks for visual question understanding. We successfully reproduced state-of-the-art results and introduced a routing agent to an existing framework. This agent performs an additional decision making before the Vision-and-Language Model (VLM) is called, which reduces redundant cropping processing time and enhances overall accuracy.

Key Results:
- Applied dynamic routing frameworks and decision algorithms to multi-agent visual reasoning tasks.  
- Achieved a 7% improvement in accuracy and reduced processing time by 50% compared to state-of-the-art methods.  
- The routing mechanism is directly applicable to the inference process and works effectively with different reasoning agents.

[Poster](/files/machi_poster.pdf) [Github](https://github.com/szujuchen/Rice-MACHI-Program)

---

## Information Retrieval Lab — National Taiwan University, Taiwan  
Special Research Student | Sep. 2023 – Jan. 2025 | Advisor: Dr. Pu Jen Cheng

During my time at the IR lab, I conducted two primary projects under the guidance of Dr. Pu-Jen Cheng.

### Project 1: Personalized Recommendation System
This project focused on developing a personalized music recommendation algorithm. I used the power of Large Language Models (LLMs) to extract additional information from user queries to retrieve more semantically relevant search results. I then combined this with user behavior and historical data to deliver the final recommendations.

Key Results:
- Preprocessed a subset of the Spotify Million Playlist Dataset, which included 337,683 tracks from over 30,000 playlists.
- Utilized ChatGPT-3.5 API as the LLM keyword extension model and trained a LightGCN model to capture user behaviors.
- Our recommendation results successfully provided a diverse selection of songs from the same music genre, avoiding the typical results from existing platforms like YouTube or Spotify.

[Poster](/files/pjlab_poster.pdf) [Github](https://github.com/szujuchen/Special-Research)

---

### Project 2: Image Retrieval Indexing

This project involved researching a new indexing strategy for image retrieval. Inspired by the paper [IRGen](https://arxiv.org/abs/2303.10126), which uses a VQVAE mechanism to turn images into individual indexes. I experimented with adding a contrastive learning algorithm into the encoding and retrieval steps.

Key Results:
- Designed and implemented a contrastive learning algorithm in both the VQVAE encoding step and the retrieval model learning step.
- Experimented with different negative item selection strategies for contrastive learning, which included selecting random negatives, the highest probability negatives, and all negatives from the highest-ranking category.
- Achieved an overall 2% improvement in the retrieval performance's F1 score. 

[Github](https://github.com/szujuchen/Special-Research)