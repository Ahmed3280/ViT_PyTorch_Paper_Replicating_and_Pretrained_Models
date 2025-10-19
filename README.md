# VisionTransformer-PyTorch-Reproducing-the-ViT-Paper-From-Scratch-Pretrained
A PyTorch implementation replicating the Vision Transformer (ViT) paper.
This project explores both a from scratch implementation and experiments using torchvision’s pretrained ViT models, including the DEFAULT and SWAG pretrained weights.

🚀 Project Overview

🔥 Implemented Vision Transformer (ViT) architecture from scratch using PyTorch
🧠 Used torchvision pretrained ViT (DEFAULT) and SWAG-pretrained ViT as feature extractors
📊 Trained all models on 20% of the dataset for fair comparison
📈 Visualized loss and accuracy curves to analyze convergence and generalization

📈 Results Summary

ViT (DEFAULT Pretrained)
✅ Final Train Accuracy: 98.05%
✅ Final Test Accuracy: 93.89%
🏆 Best Test Accuracy: 97.66% at Epoch 5
🕐 Epochs: 10

ViT (SWAG Pretrained)
✅ Final Train Accuracy: 98.22%
✅ Final Test Accuracy: 98.67%
🏆 Best Test Accuracy: 98.67% (Epochs 6–10)
🕐 Epochs: 10

💡 Insights

🔹 Both pretrained models achieved strong generalization with minimal overfitting
🔹 The SWAG pretrained ViT converged faster and reached higher accuracy with fewer epochs
🔹 Results align with the findings from the original ViT paper, highlighting the power of large scale pretraining for efficient fine-tuning
