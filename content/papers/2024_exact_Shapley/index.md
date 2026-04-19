---
title: "Machine learning models with distinct Shapley value explanations decouple feature attribution and interpretation for chemical compound predictions" 
date: 2024-08-21
tags: ["ML","xAI", "cheminformatics", "Shapley Values"]
author: ["Jannik P. Roth", "Jürgen Bajorath" ]
description: "A method for the exact calculation of Shapley Values for Support Vector Machines is introduced and tested for compound prediction tasks. Published in Cell Reports Physical Science, 2024" 
summary: "A method for the exact calculation of Shapley Values for Support Vector Machines is introduced and tested for compound prediction tasks."
cover:
    image: "roth_2024_sveker.jpg"
    alt: "Workflow of the porposed method, after the activity prediction, Shapley Values are calculated which are then mapped to chemical substructures."
    relative: true
editPost:
    URL: "https://www.cell.com/cell-reports-physical-science/home"
    Text: "Cell Press Physical Science"

---

---

##### Download

+ [Paper](https://doi.org/10.1016/j.xcrp.2024.102110)
+ [Code](https://doi.org/10.5281/zenodo.12515232)
+ [Datasets and Analysis](https://doi.org/10.5281/zenodo.11618504)

---

##### Abstract

Explaining black box predictions of machine learning (ML) models is a topical issue in artificial intelligence (AI) research. For the identification of features determining predictions, the Shapley value formalism originally developed in game theory is widely used in different fields. Typically, Shapley values quantifying feature contributions to predictions need to be approximated in machine learning. We introduce a framework for the calculation of exact Shapley values for 4 kernel functions used in support vector machine (SVM) models and analyze consistently accurate compound activity predictions based on exact Shapley values. Dramatic changes in feature contributions are detected depending on the kernel function, leading to mostly distinct explanations of predictions of the same test compounds. Very different feature contributions yield comparable predictions, which complicate numerical and graphical model explanation and decouple feature attribution and human interpretability.

---

##### Citation

Roth, Jannik P., and Jürgen Bajorath. "Machine learning models with distinct Shapley value explanations decouple feature attribution and interpretation for chemical compound predictions." *Cell Reports Physical Science* 5.8 (2024).

```latex
@article{roth2024machine,
  title={Machine learning models with distinct Shapley value explanations decouple feature attribution and interpretation for chemical compound predictions},
  author={Roth, Jannik P and Bajorath, J{\"u}rgen},
  journal={Cell Reports Physical Science},
  volume={5},
  number={8},
  year={2024},
  publisher={Elsevier}
  doi={10.1016/j.xcrp.2024.102110}
}
```

---

##### Additional Resources

+ [Press Release (german)](https://www.uni-bonn.de/de/neues/148-2024)
