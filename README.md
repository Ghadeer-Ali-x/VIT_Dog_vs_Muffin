#  Dog vs. Muffin Classifier: Vision Transformer (ViT) from Scratch

This repository contains a complete implementation of a Vision Transformer (ViT) to solve the classic "Chihuahua vs. Muffin" computer vision challenge. The model was built and trained from scratch using TensorFlow/Keras, achieving a remarkable 88% accuracy without using pre-trained weights.

##  Highlights
* Model Architecture: Pure Vision Transformer (not a CNN).
* Accuracy: 88% on the test set.
* Scale: Classified ~1300 test images.
* Custom Preprocessing: Integrated within the model for seamless inference.

## Architecture Overview
The model follows the original ViT paper architecture, adapted for efficient training on smaller datasets:
1. Patch Embedding: Dividing images into fixed-size patches.
2. Positional Encoding: Providing the model with spatial information.
3. Transformer Encoder: A stack of 12 Transformer layers featuring:
    * Multi-Head Self-Attention (MHSA) to capture global dependencies.
    * Multi-Layer Perceptron (MLP) for non-linear feature mapping.
4. Classification Head: Final MLP layer for binary classification (Chihuahua vs. Muffin).



##  Dataset & Results
The model was trained on the "Dogs vs Muffins" dataset. 
* Training Platform: Google Colab (GPU accelerated).
* Final Performance: 88% Test Accuracy.

## How to Use
1. Clone the repository:
   `bash
   git clone [https://github.com/Ghadeer-Ali-x/ViT-Dog-vs-Muffin.git](https://github.com/Ghadeer-Ali-x/ViT_Dog_vs_Muffin.git)

## Dataset
The dataset used in this project is the Dogs vs Muffins dataset. 
You can download it directly from Kaggle: [[Link to Dataset](https://www.kaggle.com/competitions/cs-460-muffin-vs-chihuahua-classification-challenge/data)]
