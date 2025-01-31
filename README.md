# **Handwritten Digit Recognition - Paper Review & Code Improvement**

## 📌 Project Description  
This repository contains a review and improvement of the paper _"Assessing Four Neural Networks on Handwritten Digit Recognition Dataset (MNIST)"_  
The research focuses on comparing **CNN** and **DenseNet** for **handwritten digit recognition** and improving model accuracy through **data augmentation** to enhance generalization across datasets.  

## 📂 Repository Structure  
- 📄 **Paper Review PDF** (`Paper Review.pdf`)  
  - A comprehensive review of the original paper, highlighting findings, methodology, and results.  
- 🖥️ **Code Review** (`Code Review.ipynb`)  
  - An improved version of the original implementation with enhancements in model architecture, preprocessing, and evaluation.  
- 📁 **Original Paper & Code** (`Handwriting-Analysis-master/`)  
  - A folder containing the original research paper and its source code.  

## 📝 Summary of Findings  
- **CNN vs. DenseNet:** DenseNet outperforms CNN, particularly when combined with data augmentation.  
- **Data Augmentation:** Significantly improves model generalization, especially on the USPS dataset.  
- **Best Model:** DenseNet with data augmentation achieves the highest accuracy across MNIST and USPS.  
- **Limitations:** The study does not explore Transformer-based architectures and is limited to MNIST and USPS datasets.  

## 📌 Future Work 
- Exploring more advanced architectures like Transformers for digit recognition.
- Expanding evaluation with additional datasets for better generalization.
- Fine-tuning hyperparameters to optimize model performance. 
