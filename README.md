What We Did : <br>
This project explores semi-supervised learning (SSL) for brain tumor classification from MRI scans using only 10% labeled data. We compared 5 methods on the Sartaj Brain Tumor MRI Dataset (Kaggle) with ResNet50 as the backbone across all experiments. <br>
Dataset Source: Sartaj Brain Tumor MRI Dataset (Kaggle)  <br>
Classes: Glioma, Meningioma, No Tumor, Pituitary <br>
Train: 5,600 images | Test: 1,600 images  <br>
Labeled: 560 images (10%) | Unlabeled: 5,040 images (90%)  <br>
Algorithms used: Transfer Learning, Pseudo-Labeling, FixMatch, Mean Teacher, FlexMatch, Mean Teacher+FixMatch Hybrid, Stratified Sampling, Cosine Annealing LR Scheduling, Adam Optimization. <br>
Stack : Python · PyTorch · ResNet50 · Google Colab · NVIDIA T4 GPU 
