# COS30082_Bird_Species_Classification

COS30082 AML Assignment 1 - Bird Species Classification
Done by Leonardo Liew 102781996

This assignment focuses on addressing the problem of overfitting in a bird species image classification task. A pretrained convolutional neural network (CNN) model is used as the baseline, and the goal is to improve its generalization performance through systematic experimentation and model refinement. Overfitting occurs when a model performs well on training data but fails to generalize to unseen validation data, often due to limited data diversity or excessive model complexity.

Refer to training.ipynb for source code

Several strategies are explored, including data augmentation, transfer learning with frozen and unfrozen layers, regularization techniques such as dropout and weight decay, and learning rate tuning during fine-tuning. The training and validation performances are analyzed across epochs to identify overfitting trends, and a confusion matrix is used to further investigate misclassifications. The final objective is to achieve a balanced model with improved validation accuracy while minimizing the gap between training and validation performance.

Due to size reasons, the model is not uploaded to GitHub but to HuggingFace where
you can try out the model right away.

HuggingFace Link - https://huggingface.co/spaces/LeoFades/COS30082_Bird_Species_Classification
YouTube Link - https://youtu.be/RZbk90Mvp5g
