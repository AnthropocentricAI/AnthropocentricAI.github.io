---
layout: post
title:  Available FAT software
categories:
tags: fairness accountability transparency software
author: Kacper
---

* content
{:toc}

A list of available fairness, accountability and transparency software packages:<!--more-->

## Transparency (interpretability and explainability) ##
### Algorithms ###

- [Anchor](https://github.com/marcotcr/anchor);
- [LIME](https://github.com/marcotcr/lime);
- Individual Conditional Expectation Plot -- [ICE](https://github.com/AustinRochford/PyCEbox);
- [Forestspy](https://github.com/jvns/forestspy).

### Packages ###
- [Skater](https://github.com/datascienceinc/Skater):
    * feature importance,
    * partial dependance plots,
    * LIME,
    * relevance propagation & integrated gradient,
    * bayesian rule lists;
- [eli5](https://github.com/TeamHG-Memex/eli5):
    * LIME,
    * permutation importance;
- [shap](https://github.com/slundberg/shap) (**this one is really nice**: it has great visualisations, examples and sample notebooks):
    * LIME,
    * Shapley sampling values,
    * DeepLIFT,
    * QII,
    * Layer-wise relevance propagation,
    * Shapley regression values,
    * Tree interpreter.

## Fairness ##
- [fairlearn](https://github.com/Microsoft/fairlearn);
- [fairml](https://github.com/adebayoj/fairml);
- [fairtest](https://github.com/columbia/fairtest):
    * developed by Columbia University,
    * uses Python and calls R from Python -- it's fairly difficult to run because of this dependency;
- [BlackBoxAuditing](https://github.com/algofairness/BlackBoxAuditing):
    * there's a FAT* 2018 tutorial that uses this package [here](https://algofairness.github.io/fatconference-2018-auditing-tutorial/),
    * [Certifying and removing disparate impact](https://arxiv.org/pdf/1412.3756.pdf),
    * [Auditing Black-box Models for Indirect Influence](https://arxiv.org/pdf/1602.07043.pdf),
    * implements *Gradient Feature Auditing*;
- [fairness-comparison](https://github.com/algofairness/fairness-comparison):
    * three naive Bayes approaches for discrimination-free classification,
    * [A comparative study of fairness-enhancing interventions in machine learning](https://arxiv.org/abs/1802.04422).
