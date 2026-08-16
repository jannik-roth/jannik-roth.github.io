---
title: "Chemically Interpretable Explanations for Molecular Property Prediction via Fragment-Level Shapley Values" 
date: 2026-04-21
tags: ["ML","AI", "cheminformatics", "Shapley Values", "eXplainable Artificial Intelligence (XAI)"]
author: ["Jannik P. Roth"]
description: "This work introduces a fragment-level Shapley value framework that enables the exact computation of feature contributions at the level of chemically meaningful fragments for molecular property predictions without relying on sampling or feature imputation. Published in Journal of Chemical Information and Modeling, 2026" 
summary: "This work introduces a fragment-level Shapley value framework that enables the exact computation of feature contributions at the level of chemically meaningful fragments for molecular property predictions without relying on sampling or feature imputation."
cover:
    image: "roth_2026_fragment_shapley.jpg"
    alt: "Developing a fragment-level framework for the calculation of exact Shapley Values."
    relative: true
editPost:
    URL: "https://pubs.acs.org/jcisd8"
    Text: "Journal of Chemical Information and Modeling"

---

---

##### Download

+ [Paper](https://doi.org/10.1021/acs.jcim.6c01425)
+ [Code](https://github.com/jannik-roth/FragShapley)

---

##### Abstract

Machine learning has emerged as a powerful approach for molecular property prediction and drug discovery. However, the black-box nature of many machine learning models limits their interpretability, trustworthiness, and adoption in interdisciplinary research settings. This is especially the case in molecular machine learning, where explanations of model predictions are used for informed decision-making and downstream tasks. Shapley values, originating from cooperative game theory, provide a principled framework for attributing model predictions to individual input features. However, existing Shapley value-based explanations for molecular machine learning often rely on sampling-based approximations or operate at the level of abstract features, which can reduce attribution stability and limit chemical interpretability and actionability. Here, we introduce a fragment-level Shapley value framework that enables the exact computation of feature contributions at the level of chemically meaningful fragments for molecular property predictions without relying on sampling or feature imputation. By decomposing molecules into fragments, the proposed approach yields actionable explanations that can be directly related to established chemical concepts. We apply the method post hoc to random forest and graph convolutional network models using common molecular representations, including extended-connectivity fingerprints and molecular graphs. The approach is evaluated across three representative property prediction tasks: aqueous solubility, mutagenicity, and antiviral potency. Fragment-level Shapley values reproduce wellestablished chemical trends, identify known toxicophores, and enable guided molecular optimization. In addition, the method provides insights into model learning characteristics and helps delineate the applicability domain, particularly in settings with limited and structurally biased data. Overall, this work demonstrates that adapting Shapley values to chemically meaningful fragments enables interpretable explanations for molecular machine learning models, supporting molecular optimization and model validation.

---

##### Citation

Roth, Jannik P. "Chemically Interpretable Explanations for Molecular Property Prediction via Fragment-Level Shapley Values." *Journal of Chemical Information and Modeling* (2026).

```latex
@article{roth2026chemically,
  title={Chemically Interpretable Explanations for Molecular Property Prediction via Fragment-Level Shapley Values},
  author={Roth, Jannik Philipp},
  journal={Journal of Chemical Information and Modeling},
  year={2026},
  doi={10.1021/acs.jcim.6c01425}
}

```
