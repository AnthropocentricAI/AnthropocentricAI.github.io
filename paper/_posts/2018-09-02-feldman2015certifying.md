---
layout: post
title:  "Certifying and removing disparate impact"
categories:
tags: fairness
author: Kacper
paper_url: https://arxiv.org/pdf/1412.3756.pdf
---

* content
{:toc}

## Abstract ##
What does it mean for an algorithm to be biased? In U.S. law, unintentional bias is encoded via disparate impact, which occurs when a selection process has widely different outcomes for different groups, even as it appears to be neutral. This legal determination hinges on a definition of a protected class (ethnicity, gender, religious practice) and an explicit description of the process. 
When the process is implemented using computers, determining disparate impact (and hence bias) is harder. It might not be possible to disclose the process. In addition, even if the process is open, it might be hard to elucidate in a legal setting how the algorithm makes its decisions. Instead of requiring access to the algorithm, we propose making inferences based on the data the algorithm uses. 
We make four contributions to this problem. First, we link the legal notion of disparate impact to a measure of classification accuracy that while known, has received relatively little attention. Second, we propose a test for disparate impact based on analyzing the information leakage of the protected class from the other data attributes. Third, we describe methods by which data might be made unbiased. Finally, we present empirical evidence supporting the effectiveness of our test for disparate impact and our approach for both masking bias and preserving relevant information in the data. Interestingly, our approach resembles some actual selection practices that have recently received legal scrutiny.<!--more-->

## BibTeX ##
```
@inproceedings{feldman2015certifying,
  title={Certifying and removing disparate impact},
  author={Feldman, Michael and Friedler, Sorelle A and Moeller, John and Scheidegger, Carlos and Venkatasubramanian, Suresh},
  booktitle={Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining},
  pages={259--268},
  year={2015},
  organization={ACM}
}
```

## Notes ##
- See the software related post [here]({% post_url /fat/2018-09-02-fat-software %}#fairness).
