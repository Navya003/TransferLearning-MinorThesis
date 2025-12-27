# TransferLearning-MinorThesis
Transfer Learning for Improved Image Classification: Summer Internship Report

This repository contains the comprehensive documentation, final report, and presentation for my summer internship project focused on optimizing Transfer Learning (TL) pipelines for image classification.

## 🚀 Project Overview

This project involved the re-engineering and benchmarking of a modular deep learning pipeline. Originally conceived for COVID-19 detection in radiological images, the framework was evolved into a domain-agnostic tool. By leveraging Transfer Learning, we evaluated five major CNN architectures to identify the optimal balance between classification accuracy and computational efficiency.

## Key Results

- DenseNet121 achieved the highest generalization with 97.8% CV Accuracy.

- EfficientNetB0 was identified as the Optimal Choice for deployment, training 2.4x faster than VGG19 while maintaining a competitive 97.0% accuracy.

## 📂 Repository Contents

- Summer_Thesis_Final.pdf: The complete internship report detailing the theoretical background, methodology, and experimental analysis.

- RadImageNet.ipynb: Google Colab notebook containing the full implementation, training logs, and evaluation metrics using FASHION_MNIST.

- Summer Internship Presentation.pptx: The final presentation I did for the internship evaluation.

## 🛠 Related Repositories

The core source code, modular Python scripts, and technical framework development can be found in the main project repository:

🔗 [radImageNet Repository](https://github.com/Navya003/RadImageNet)

## 🧠 Methodology

1. Modular Design: Development of a 5-stage pipeline (Data Loading, Model Building, Training, Evaluation, Deployment).

2. Unbiased Benchmarking: Utilized the FASHION_MNIST dataset to isolate architectural performance from clinical data biases.

3. Cross-Validation: Implemented 5-Fold Cross-Validation to ensure the robustness and reproducibility of results.

4. Model Comparison: Evaluated VGG16, VGG19, ResNet50, DenseNet121, and EfficientNetB0.

## 🎓 Acknowledgments

This work was completed during a summer internship under the supervision of Dr. Andrew Lynn at the School of Computational and Integrative Sciences, Jawaharlal Nehru University (JNU), New Delhi.

Navya Tyagi M.Sc. Data Science, Amity University
