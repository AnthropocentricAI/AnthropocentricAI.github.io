---
layout: post
title:  "A comparative study of fairness-enhancing interventions in machine learning"
categories:
tags: fairness
author: Kacper
paper_url: https://arxiv.org/abs/1802.04422
---

* content
{:toc}

## Abstract ##
Computers are increasingly used to make decisions that have significant impact in people's lives. Often, these predictions can affect different population subgroups disproportionately. As a result, the issue of fairness has received much recent interest, and a number of fairness-enhanced classifiers and predictors have appeared in the literature. This paper seeks to study the following questions: how do these different techniques fundamentally compare to one another, and what accounts for the differences? Specifically, we seek to bring attention to many under-appreciated aspects of such fairness-enhancing interventions. Concretely, we present the results of an open benchmark we have developed that lets us compare a number of different algorithms under a variety of fairness measures, and a large number of existing datasets. We find that although different algorithms tend to prefer specific formulations of fairness preservations, many of these measures strongly correlate with one another. In addition, we find that fairness-preserving algorithms tend to be sensitive to fluctuations in dataset composition (simulated in our benchmark by varying training-test splits), indicating that fairness interventions might be more brittle than previously thought.
<!--more-->

## BibTeX ##
```
@article{friedler2018comparative,
  title={A comparative study of fairness-enhancing interventions in machine learning},
  author={Friedler, Sorelle A and Scheidegger, Carlos and Venkatasubramanian, Suresh and Choudhary, Sonam and Hamilton, Evan P and Roth, Derek},
  journal={arXiv preprint arXiv:1802.04422},
  year={2018}
}
```

## Notes ##
- See the software related post [here]({% post_url /fat/2018-09-02-fat-software %}#fairness).
