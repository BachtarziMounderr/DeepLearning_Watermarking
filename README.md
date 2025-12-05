# DeepLearning_Watermarking
Deep Learning-Based Watermarking Workshop
University: Abdelhamid Mehri – Constantine 2  
Program: Master 2 Data Science & Artificial Intelligence  
Course: Intelligent Techniques for Fighting Fraud and Corruption (ITFFC)  
Instructor: Dr. Bouchra Guelib  
Student: Mounder Siradj Eddine Bachtarzi  
Date: 2025  
Reached results : -Medical invisibility: PSNR ≈ 49 dB
                  -Watermark recovery: PSNR ≈ 40 dB, SSIM ≈ 0.82 
                  -Retrieval accuracy: 85–90%
---

## Workshop Objective/Results
Deep Learning-Based Feature-Space Watermarking for Medical Images

This project implements a complete deep-learning pipeline for secure and robust watermarking of medical images.
It includes preprocessing, optional GAN-based augmentation, deep feature extraction, and a learnable encoder–decoder watermark embedding system.

The project evaluates multiple architectures (CNN, ViT, CBAM) and shows that ResNet50 + CBAM provides the best watermark invisibility and recoverability.

   Included Components

Dataset preprocessing & EDA

(Optional) GAN-based data augmentation

Deep feature extraction using:

ResNet50

Vision Transformer (ViT)

ResNet50 + CBAM (best-performing)

Feature-space watermark embedding with:

Learnable encoder for watermark injection

Learnable decoder for watermark recovery

Quality metrics: MSE, PSNR, SSIM

Robustness evaluation: noise, scaling, distortions

Watermark retrieval via cosine similarity

   Key Findings

ViT features are too abstract for reliable watermark recovery.

ResNet50 + CBAM achieves outstanding results:

Medical invisibility: PSNR ≈ 49 dB

Watermark recovery: PSNR ≈ 40 dB, SSIM ≈ 0.82

Robustness under attack: watermark remains identifiable

Retrieval accuracy: 85–90%

   What This Project Demonstrates

A complete, functional pipeline for feature-space watermarking, showing how deep models can embed structured information into medical image representations while maintaining:

Invisibility

Recoverability

Robustness

This approach can be applied to medical image security, ownership protection, and integrity verification
