+++
title="Text is an Image: Augmentation via Embedding Mixing"
date=2020-01-01
slug="text-is-an-image"
description="K. Zhao, V. Lialin, A. Rumshisky., MIT PRIMES, 2020"

[extra]
link = "https://math.mit.edu/research/highschool/primes/materials/2020/Zhao-Lialin-Rumshisky.pdf"
link_description = "Paper link"
+++

Data augmentation techniques are essential for computer vision, yielding signif-
icant accuracy improvements with little engineering costs. However, data aug-
mentation for text has always been tricky. Synonym replacement techniques re-
quire a good thesaurus and domain-specific rules for synonym selection from the
synset, while backtranslation techniques are computationally expensive and re-
quire a good translation model for the language in interest.
In this paper, we present simple text augmentation techniques on the embed-
dings level, inspired by mixing-based image augmentations. These techniques
are language-agnostic and require little to no hyperparameter tuning. We evaluate
the augmentation techniques on IMDB and GLUE tasks, and the results show that
the augmentations significantly improve the score of the RoBERTa model.

<!-- more -->

### Citation:
```bibtex
@misc{donahue2019injecting,
    title={Text is an Image: Augmentation via Embedding Mixing},
    author={Kevin Zhao and Vladislav Lialin and Anna Rumshisky},
    year={2020},
}
```
