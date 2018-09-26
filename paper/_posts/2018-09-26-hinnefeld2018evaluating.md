---
layout: post
title:  "Evaluating Fairness Metrics in the Presence of Dataset Bias"
categories:
tags: fairness
author: Peter
paper_url: https://arxiv.org/pdf/1809.09245.pdf
---

* content
{:toc}

## Abstract ##
Data-driven algorithms play a large role in decision making across a variety of industries. Increasingly, these algorithms are being used to make decisions that have significant ramifications for people's social and economic well-being, e.g. in sentencing, loan approval, and policing. Amid the proliferation of such systems there is a growing concern about their potential discriminatory impact. In particular, machine learning systems which are trained on biased data have the potential to learn and perpetuate those biases. A central challenge for practitioners is thus to determine whether their models display discriminatory bias. Here we present a case study in which we frame the issue of bias detection as a causal inference problem with observational data. We enumerate two main causes of bias, sampling bias and label bias, and we investigate the abilities of six different fairness metrics to detect each bias type. Based on these investigations, we propose a set of best practice guidelines to select the fairness metric that is most likely to detect bias if it is present. Additionally, we aim to identify the conditions in which certain fairness metrics may fail to detect bias and instead give practitioners a false belief that their biased model is making fair decisions.
<!--more-->

## BibTeX ##
```
@article{hinnefeld2018evaluating,
    author = { {Hinnefeld}, J.~H. and {Cooman}, P. and {Mammo}, N. and {Deese}, R.},
    title = "{Evaluating Fairness Metrics in the Presence of Dataset Bias}",
    journal = {ArXiv e-prints},
    eprint = {1809.09245},
    year = 2018,
    month = sep
}
```
