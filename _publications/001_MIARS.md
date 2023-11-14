---
pub_date: 2021
title: "Membership Inference Attacks Against Recommender Systems"
excerpt: 'We take the first step quantifying the privacy risks of recommender systems through the lens of membership inferencek.'
venue: 'ACM CCS'
date: 2021-09-16
paperurl: 'https://arxiv.org/abs/2109.08045'
---
Recently, recommender systems have achieved promising performances and become one of the most widely used web applications. However, recommender systems are often trained on highly sensitive user data, thus potential data leakage from recommender systems may lead to severe privacy problems. 
In this paper, we make the first attempt on quantifying the privacy leakage of recommender systems through the lens of membership inference. In contrast with traditional membership inference against machine learning classifiers, our attack faces two main differences. First, our attack is on the user-level but not on the data sample-level. Second, the adversary can only observe the ordered recommended items from a recommender system instead of prediction results in the form of posterior probabilities. To address the above challenges, we propose a novel method by representing users from relevant items. Moreover, a shadow recommender is established to derive the labeled training data for training the attack model. Extensive experimental results show that our attack framework achieves a strong performance. In addition, we design a defense mechanism to effectively mitigate the membership inference threat of recommender systems.

[Download paper here](https://arxiv.org/abs/2109.08045)
