# Few-Shot Classification via Unsupervised Deep Belief Networks on the Omniglot Dataset

## Overview

This project explores Few-Shot Learning techniques using Unsupervised Deep Belief Networks (DBNs) on the Omniglot dataset.

The objective of the project was to investigate how unsupervised representation learning can improve image classification performance in low-data scenarios where only a limited number of labelled samples are available.

The implementation focuses on:
- unsupervised feature extraction
- hierarchical representation learning
- Deep Belief Networks
- few-shot image classification
- low-data generalization

---

## Academic Result

This project obtained the maximum possible grade in the course evaluation.

The work was particularly recognized for:
- the quality of the implementation
- the experimental analysis
- the representation learning pipeline
- the methodological design
- the clarity of the evaluation process

---

## Main Topics

- Few-Shot Learning
- Deep Belief Networks (DBNs)
- Restricted Boltzmann Machines (RBMs)
- Unsupervised Learning
- Representation Learning
- Omniglot Dataset
- Feature Extraction
- Low-Data Classification

---

## Dataset

The experiments were performed using the:

```text
Omniglot Dataset
```

a well-known benchmark dataset for few-shot learning and character recognition tasks.

The dataset contains:
- handwritten characters
- multiple alphabets
- highly diverse symbol structures
- low-sample classification challenges

making it particularly suitable for evaluating generalization capabilities.

---

## Model Architecture

The project implemented a Deep Belief Network architecture composed of:
- Restricted Boltzmann Machines (RBMs)
- hierarchical latent representations
- layer-wise unsupervised pretraining

The model was designed to:
- learn robust feature representations
- capture latent visual structures
- improve classification under scarce labelled data conditions

---

## Training Pipeline

The workflow included:

1. Data preprocessing
2. Unsupervised pretraining
3. Hierarchical feature extraction
4. Representation learning
5. Few-shot classification evaluation

The layer-wise unsupervised training strategy allowed the network to learn meaningful representations before downstream classification.

---

## Representation Learning

The experiments demonstrated that the model successfully learned:
- stroke-level visual patterns
- structural similarities between characters
- abstract latent representations
- discriminative embeddings

These representations improved classification performance even with limited labelled examples.

---

## Results

The experiments showed that:
- unsupervised pretraining improves downstream classification
- learned embeddings increase class separability
- DBNs can generalize effectively under low-data conditions
- representation learning significantly improves few-shot performance

The project also highlighted the importance of:
- latent feature extraction
- hierarchical learning
- representation quality
- unsupervised initialization

for building robust few-shot learning systems.

---

## Limitations

Several limitations were identified during experimentation:

- computational complexity
- training instability in deeper architectures
- sensitivity to hyperparameter tuning
- scalability limitations compared to modern transformer-based models

Despite these limitations, the experiments demonstrated the effectiveness of DBNs for representation learning in few-shot scenarios.

---

## Repository Structure

```text
few-shot-classification-dbn-omniglot/
├── notebook/
│   └── few_shot_classification.ipynb
├── results/
│   ├── accuracy_results.txt
│   ├── model_analysis.txt
│   └── training_curves.png
├── images/
│   └── architecture.png
├── requirements.txt
└── README.md
```

---

## Skills Developed

- Few-Shot Learning
- Deep Belief Networks
- Restricted Boltzmann Machines
- Representation Learning
- Unsupervised Learning
- Feature Extraction
- Low-Data Classification
- Deep Learning Workflows

---

## Technologies

- Python
- PyTorch
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Conclusions

This project provided practical experience with unsupervised deep learning techniques for representation learning and few-shot classification.

The experiments demonstrated how hierarchical latent representations can improve classification performance in low-data scenarios and highlighted the importance of unsupervised pretraining in deep learning systems.
