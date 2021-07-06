---
layout: archive
title: "Key Projects"
permalink: /research/
author_profile: true
---

## Misleading News Headline Detection

In digital environments where information is shared online, news headlines play an essential role in the selection and diffusion of news articles. If the short text does not represent the main content correctly, it can be misleading and adversely affect the entire news reading experiences.
Therefore, we tackle the headline incongruity problem, in which a headline makes an irrelevant or opposite claim to the part of the main content. 
In particular, we implement deep learning models that detect the incongruity between a headline and a body text. Motivated by the innate hierarchical structure of news articles, we first design an attention-based hierarchical dual encoder that models a length news article through two-level recurrent neural networks (AAAI'19). We extend the hierarchical approach by a graph neural network (GHDE) where headlines and paragraphs are connected. 

![Model structure](/images/fig_ghde_model.jpg)

In order to convey the results of the machine learning model to potential readers in an effective manner, we implement BaitWatcher, a lightweight web interface that guides readers in estimating the likelihood of incongruence before clicking the headline (FNDM). You can watch a demonstration of the web interface in the following video.

[![Link to the YouTube video](https://img.youtube.com/vi/XehbK4YqsYI/0.jpg)](https://www.youtube.com/watch?v=XehbK4YqsYI)

### Publications

- [Learning to Detect Incongruence in News Headline and Body Text via a Graph Neural Network. In IEEE Access, 2021.](https://ieeexplore.ieee.org/abstract/document/9363185/)
- [Detecting incongruity between news headline and body text via a deep hierarchical encoder. In AAAI, 2019.](https://www.aaai.org/ojs/index.php/AAAI/article/view/3756)
- [BaitWatcher: A Lightweight Web Interface for the Detection of Incongruent News Headlines. In Springer Book Chapters on Disinformation, Misinformation, and Fake News in Social Media. 2020.](https://link.springer.com/chapter/10.1007/978-3-030-42699-6_12)

### Code

- [GHDE](https://github.com/minwhoo/detecting-incongruity-gnn)
- [AHDE](https://github.com/david-yoon/detecting-incongruity)
- [BaitWatcher](https://github.com/bywords/BaitWatcher)



<!--

## Modeling customer satisfaction in live chat customer services
#### Published at CIKM'15 and WWW'18

Customer service operation is a key management function to optimize customer satisfaction, and therefore many companies employ live chats as a means of support service. Using more than 170,000 chat sessions between a customer and an agent in a live chat service of Samsung Electronics in the US, we investigated what leads to dissatisfaction of a customer in a chat from the rich text data and self-reported satisfaction scores.
In the first study (CIKM'15), we identified that sentiments or moods provide a predictive signal for the dissatisfaction from analyses of machine learning models.

Next, we focused on the vulnerability of the customer rating mechanism used for evaluating overall satisfaction (WWW'18). In the service, the majority of the customers (83.78%) were left the chat without a response. How was likely their experience? To answer the question, we proposed deep learning models for estimating customer satisfaction of unlabeled sessions. Using the model, we made a novel finding that while labeled sessions contributed by a small fraction of customers received overwhelmingly positive reviews, the majority of unlabeled sessions would have received lower ratings by customers.

This study not only helps companies detect dissatisfied customers on live chat services at an early stage, but also makes an empirical contribution to discovering potential biases in live chat services. 

![Distribution of customer satisfaction across different types of datasets](/images/www18_dist.png)

[[Paper (CIKM'15)]](https://dl.acm.org/doi/abs/10.1145/2806416.2806621)
[[Paper (WWW'18)]](https://dl.acm.org/doi/abs/10.1145/3184558.3186579)
[[Code (WWW'18)]](https://github.com/bywords/Positivity-Bias-Livechat)



## Identifying behavioral factors driving longevity in online services
#### Ph.D. dissertation: published at CSCW'16 and WWW'17

Having a substantial number of loyal users is key to the success of online social platforms. When building a social platform where users enjoy over a long period, it is crucial to identify predictive signals for long-term engagement, which we call *user longevity*.
I analyzed behavioral records of users in three different social services and tried to predict the longevity of their users: fitness apps (CSCW'16), online multiplayer games (WWW'17), and online discussion communities.
From each different platform, we made a common finding on the importance of having a social connection with peers for long-term usage. For example, the figure below illustrates the importance of different groups of features for long-term usages over different stages of gameplay. While achievement-related features were important in the early stages, the importance of social factors become more dominant when the users reached the highest level. The findings and data analytics could contribute to other platforms retaining their users and eventually succeed.

![Importance of three different factors over time](/images/www17_perf.png)

[[Paper (CSCW'16)]](https://dl.acm.org/doi/abs/10.1145/2818048.2819921)
[[Paper (WWW'17)]](https://dl.acm.org/doi/abs/10.1145/3041021.3054176)

-->
