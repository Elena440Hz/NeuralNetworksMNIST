This project compares three deep learning approaches for medical image classification on MedMNIST: a CNN
built from scratch (with BatchNorm, Dropout, and Weight Decay), transfer learning using a pretrained CNN
(feature extraction vs. fine-tuning), and a Vision Transformer (DeiT-tiny). Key aspects include designing conv
blocks, handling small-resolution images, resizing for Transformers, and evaluating via accuracy, loss curves,
and confusion matrices. The goal is to understand how architecture choice, regularization, and
pretraining affect generalization on small medical datasets. .
