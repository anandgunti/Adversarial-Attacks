
# Investigating Adversarial Attacks on neural network:Exploring Explainable AI and The Impact of Feature Selection using MATLAB

## Overview
This repository contains the code and resources for the dissertation titled "Investigating Adversarial Attacks on neural network:
Exploring Explainable AI and The Impact of Feature Selection using MATLAB". The dissertation investigates the impact of adversarial attacks on neural network, with a focus on understanding their decision-making processes and identifying factors influencing their robustness.

## Contents
- **Code**: This directory contains the Python scripts used for the experiments and analysis conducted in the dissertation.
- **Data**: This directory includes datasets used for training and evaluation purposes. Due to size limitations, only sample datasets are provided. Full datasets can be obtained from the respective sources mentioned in the dissertation.
- **Research papers**: This directory includes additional documentation such as literature reviews.


## Literature Review

### Introduction
Understanding the behavior of deep neural networkS and their vulnerability to adversarial attacks is crucial for enhancing their robustness and reliability in practical applications. This literature review aims to provide insights into the intuitive properties of neural networks and the mechanisms behind adversarial attacks, drawing from seminal works in the field.

### Fundamentals of Adversarial Attacks
1. **Szegedy et al., 2014**: This foundational paper identified the existence of adversarial attacks, highlighting the susceptibility of neural networks to perturbations in input data.

2. **Goodfellow et al., 2015**: Building upon earlier research, this work delved deeper into the rationale behind adversarial examples, proposing the Fast Gradient Sign Method (FGSM) for efficient generation of adversarial examples. The authors also explained the phenomenon of transferability of attacks across different models.

3. **Kurakin et al., 2016**: Explored practical implications of adversarial attacks by introducing the Basic Iterative Method (BIM) for generating adversarial examples. This work provided insights into the robustness of neural networks against iterative attacks.

### Understanding Adversarial Attacks
1. **Ilyas et al., 2019**: This work contributed meaningful explanations behind adversarial attacks and their transferability across models, attributing it to non-robust features of the networks. The authors shed light on the underlying vulnerabilities of neural networks and their susceptibility to adversarial perturbations.

2. **Su et al., 2019**: Investigated the minimal changes required to generate adversarial attacks, introducing the concept of single-pixel attacks. This work provided insights into the fine-grained nature of adversarial perturbations and their impact on Neural network decision-making.

### Visualizing Adversarial Attacks
Visualizing adversarial attacks offers concrete evidence of vulnerabilities in neural network's decision-making processes. By comparing the transferability of attacks across various models, researchers can gain valuable insights into the robustness of different architectures and inform strategies for improving network security.

### Conclusion
The literature reviewed here provides a comprehensive understanding of the behavior of neural networks and the mechanisms behind adversarial attacks. By leveraging insights from these seminal works, researchers can develop more robust and reliable neural network architectures, thus advancing the field of machine learning security.

You can present these key points in your README file on GitHub to provide a concise overview of your findings. Here's a suggested format:

---

## Key Inferences

### 1. Explainable AI Insights
Explainable AI techniques offer valuable insights into the decision-making processes of neural networks, helping us understand how models interpret data and make predictions.

### 2. Nature of Untargeted Adversarial Attacks
- Models deceived by adversarial attacks tended to misclassify inputs into related categories, such as different breeds of dogs.
- Adversarial perturbations may influence the model's interpretations along existing lines of understanding, rather than inducing random errors.

### 3. Impact of Training Data Distribution
- The distribution of training data influences model predictions.
- Diverse datasets with overlapping features, such as various dog breeds, may lead to a more detailed but vulnerable understanding of categories, potentially increasing susceptibility to adversarial attacks.

### 4. Role of Non-Robust Features
- Non-robust features, such as background elements, play a crucial role in misclassification.
- Adversarial attacks may exploit these features to deceive the model.

### 5. Balancing Robust and Non-Robust Features
- Model resilience against adversarial attacks is determined by how it balances attention between robust and non-robust features.
- Effective balancing of focus between these features may lead to greater resistance against adversarial perturbations.


To present the hypotheses and their evaluation in your README file on GitHub, you can structure the information in a clear and organized manner. Here's a suggested format:

---

## Hypotheses and Evaluation

### Hypothesis 1: Dataset Distribution
**Hypothesis:** Neural networks trained on datasets with closely related classes are more susceptible to adversarial attacks due to potential feature overlap.

**Testing Methodology:**
- Trained models using transfer learning on a custom dataset comprising five distinct classes.
- Evaluated robustness against adversarial attacks.
- Analyzed model performance metrics.

**Findings:**
- Observed significant differences in model performance based on dataset quality.
- Highlighted vulnerabilities of models trained on datasets with overlapping features.

### Hypothesis 2: Pre-processing of Non-Robust Features
**Hypothesis:** Pre-processing to remove non-robust features improves model robustness against adversarial attacks.

**Testing Methodology:**
- Pre-processed images by removing backgrounds.
- Simulated targeted adversarial attacks.
- Observed model predictions and attention maps.

**Findings:**
- Pre-processing enhanced resilience against targeted attacks but had mixed results for untargeted attacks.
- Highlighted the importance of architecture-specific vulnerabilities.

### Hypothesis 3: Impact of Dropout Layers
**Hypothesis:** Inclusion of dropout layers may inadvertently increase model vulnerability to adversarial attacks.

**Testing Methodology:**
- Experimented with different dropout rates in the GoogLeNet model.
- Evaluated feature selection and model robustness.

**Findings:**
- Dropout rates affected feature importance and model resilience against adversarial attacks.
- Highlighted the challenge of balancing model generalization and robustness.

### Conclusion and Future Directions
- Emphasize the importance of understanding how model parameters and data distribution impact model robustness.
- Suggest future research directions for fine-tuning dropout values and defending against specific adversarial perturbations.

---


## Usage
1. Clone the repository:
   ```
   git clone https://github.com/anandgunti55/Adversarial-Attacks.git
   ```
2. Refer to the dissertation document for detailed explanations of the experiments and results.

