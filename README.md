#### Approach *4*
***LIME - Local Interpretable Model-Agnostic Explanations:***

***Questions for LIME according to Hohmann et al. from our point of view:***
1. **WHY**
  - Interpretability & Explainability: knowing the feature contributions to the decision helps to interpret and explain why the model makes certain decisions
  - Debbugging & Improving Models: identifying features that lead the model in a wrong direction (towards a misclassification) can help to improve the model
  - Comparing & Selecting Models
  - Education
2. **WHO**
  - Model Developers & Builders: it can help to select meaningful features respectively remove features that don't contribute to correct decisions
  - Model Users: it helps to identify which features were mainly contributing to the classifcation of a certain sample, therefore give further insights to the underlying process
  - Non-experts
3. **WHAT**
  - Computational Graph & Network Architecture
  - Learned Model Parameters
  - Individual Computational Units
  - Neurons in High-dimensional Space
  - Aggregation Information: the approach identifies the importance of all features for the final classification
4. **HOW**
  - Instance-based Analysis & Exploration: for each test instance, the feature importance can be calculated
  - Algorithms for Attribution & Feature Visualization: it is computed how the features contribute to the attribution of a test instance
5. **WHEN**
  - After Training.
6. **WHERE**
  - [arXiv](https://arxiv.org/abs/1602.04938)
  - [GitHub](https://github.com/marcotcr/lime)
