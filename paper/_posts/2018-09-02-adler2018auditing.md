---
layout: post
title:  "Auditing black-box models for indirect influence"
categories:
tags: fairness
author: Kacper
paper_url: https://arxiv.org/pdf/1602.07043.pdf
---

* content
{:toc}

## Abstract ##
Data-trained predictive models see widespread use, but for the most part they are used as black boxes which output a prediction or score. It is therefore hard to acquire a deeper understanding of model behavior, and in particular how different features influence the model prediction. This is important when interpreting the behavior of complex models, or asserting that certain problematic attributes (like race or gender) are not unduly influencing decisions. 
In this paper, we present a technique for auditing black-box models, which lets us study the extent to which existing models take advantage of particular features in the dataset, without knowing how the models work. Our work focuses on the problem of indirect influence: how some features might indirectly influence outcomes via other, related features. As a result, we can find attribute influences even in cases where, upon further direct examination of the model, the attribute is not referred to by the model at all. 
Our approach does not require the black-box model to be retrained. This is important if (for example) the model is only accessible via an API, and contrasts our work with other methods that investigate feature influence like feature selection. We present experimental evidence for the effectiveness of our procedure using a variety of publicly available datasets and models. We also validate our procedure using techniques from interpretable learning and feature selection, as well as against other black-box auditing procedures.
<!--more-->

## BibTeX ##
```
@article{adler2018auditing,
  title={Auditing black-box models for indirect influence},
  author={Adler, Philip and Falk, Casey and Friedler, Sorelle A and Nix, Tionney and Rybeck, Gabriel and Scheidegger, Carlos and Smith, Brandon and Venkatasubramanian, Suresh},
  journal={Knowledge and Information Systems},
  volume={54},
  number={1},
  pages={95--122},
  year={2018},
  publisher={Springer}
}
```

## Notes ##
- See the software related post [here]({% post_url /fat/2018-09-02-fat-software %}#fairness).
