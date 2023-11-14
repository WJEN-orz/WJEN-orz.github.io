---
pub_date: 2023
title: "Generated Distributions Are All You Need for Membership Inference Attacks Against Generative Models"
excerpt: 'We propose the first generalized membership inference attack against a variety of generative models such as generative adversarial networks, [variational] autoencoders, implicit functions, and the emerging diffusion models.'
venue: 'IEEE/CVF WACV'
date: 2024-01-04
paperurl: 'http://arxiv.org/abs/2310.19410'
---
_**Minxing Zhang**, Ning Yu, Rui Wen, Michael Backes, Yang Zhang_

Generative models have demonstrated revolutionary success in various visual creation tasks, but in the meantime, they have been exposed to the threat of leaking private information of their training data. Several membership inference attacks (MIAs) have been proposed to exhibit the privacy vulnerability of generative models by classifying a query image as a training dataset member or nonmember. However, these attacks suffer from major limitations, such as requiring shadow models and white-box access, and either ignoring or only focusing on the unique property of diffusion models, which block their generalization to multiple generative models. In contrast, we propose the first generalized membership inference attack against a variety of generative models such as generative adversarial networks, [variational] autoencoders, implicit functions, and the emerging diffusion models. We leverage only generated distributions from target generators and auxiliary non-member datasets, therefore regarding target generators as black boxes and agnostic to their architectures or application scenarios. Experiments validate that all the generative models are vulnerable to our attack. For instance, our work achieves attack AUC>0.99 against DDPM, DDIM, and FastDPM trained on CIFAR-10 and CelebA. And the attack against VQGAN, LDM (for the text-conditional generation), and LIIF achieves AUC>0.90. As a result, we appeal to our community to be aware of such privacy leakage risks when designing and publishing generative models.

[Download paper here](http://arxiv.org/abs/2310.19410)
