What We Did :
This project explores semi-supervised learning (SSL) for brain tumor classification from MRI scans using only 10% labeled data. We compared 5 methods on the Sartaj Brain Tumor MRI Dataset (Kaggle) with ResNet50 as the backbone across all experiments.
Dataset Source: Sartaj Brain Tumor MRI Dataset (Kaggle)
Classes: Glioma, Meningioma, No Tumor, Pituitary
Train: 5,600 images | Test: 1,600 images
Labeled: 560 images (10%) | Unlabeled: 5,040 images (90%)
Algorithms used: Transfer Learning, Pseudo-Labeling, FixMatch, Mean Teacher, FlexMatch, Mean Teacher+FixMatch Hybrid, Stratified Sampling, Cosine Annealing LR Scheduling, Adam Optimization.
Stack : Python · PyTorch · ResNet50 · Google Colab · NVIDIA T4 GPU
