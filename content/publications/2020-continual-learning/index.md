+++
title="Update Frequently, Update Fast: Retraining Semantic Parsing Systems in a Fraction of Time"
date=2020-10-15
slug="continual-learning"
description="V. Lialin, R. Goel, A. Simanovsky, A. Rumshisky, R. Shah, 2020"

[extra]
link = "https://arxiv.org/abs/2010.07865"
link_description = "Paper link"
+++

Currently used semantic parsing systems deployed in voice assistants can require weeks to train. Datasets for these models often receive small and frequent updates, data patches. Each patch requires training a new model. To reduce training time, one can fine-tune the previously trained model on each patch, but naive fine-tuning exhibits catastrophic forgetting - degradation of the model performance on the data not represented in the data patch. In this work, we propose a simple method that alleviates catastrophic forgetting and show that it is possible to match the performance of a model trained from scratch in less than 10% of a time via fine-tuning. The key to achieving this is supersampling and EWC regularization. We demonstrate the effectiveness of our method on multiple splits of the Facebook TOP and SNIPS datasets.

<!-- more -->

### Citation:
```bibtex
@misc{lialin2020update,
    title={Update Frequently, Update Fast: Retraining Semantic Parsing Systems in a Fraction of Time},
    author={Vladislav Lialin and Rahul Goel and Andrey Simanovsky and Anna Rumshisky and Rushin Shah},
    year={2020},
    eprint={2010.07865},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
