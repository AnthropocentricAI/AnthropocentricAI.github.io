---
layout: post
title:  "Foolbox: A python toolbox to benchmark the robustness of machine learning models"
categories:
tags: robustness accountability
author: Kacper
paper_url: https://arxiv.org/pdf/1707.04131.pdf
---

* content
{:toc}

## Abstract ##
Even today's most advanced machine learning models are easily fooled by almost imperceptible perturbations of their inputs. Foolbox is a new Python package to generate such adversarial perturbations and to quantify and compare the robustness of machine learning models. It is build around the idea that the most comparable robustness measure is the minimum perturbation needed to craft an adversarial example. To this end, Foolbox provides reference implementations of most published adversarial attack methods alongside some new ones, all of which perform internal hyper-parameter tuning to find the minimum adversarial perturbation. Additionally, Foolbox interfaces with most popular deep learning frameworks such as PyTorch, Keras, TensorFlow, Theano and MXNet and allows different adversarial criteria such as targeted misclassification and top-k misclassification as well as different distance measures. The code is licensed under the MIT license and is openly available at [this https URL](https://github.com/bethgelab/foolbox). The most up-to-date documentation can be found at [this http URL](http://foolbox.readthedocs.io/).
<!--more-->

## BibTeX ##
```
@article{rauber1707foolbox,
  title={Foolbox: A python toolbox to benchmark the robustness of machine learning models},
  author={Rauber, Jonas and Brendel, Wieland and Bethge, Matthias},
  journal={http://arxiv.org/abs/1707.04131}
}
```
