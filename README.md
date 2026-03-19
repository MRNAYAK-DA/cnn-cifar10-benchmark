# cnn-cifar10-benchmark
Benchmarking CNN architectures (ResNet18, VGG16, MobileNetV2, EfficientNet-B0) on CIFAR-10 with transfer learning and adversarial robustness insights.
CNN Benchmark on CIFAR-10 (STAAR Project)

Overview
--------
This project evaluates and compares the performance of several convolutional neural network (CNN) architectures on the CIFAR-10 dataset. All models are trained and evaluated under identical experimental conditions to ensure fair comparison.

Models Compared
---------------
- SimpleCNN (baseline model)
- ResNet-18
- VGG-16
- MobileNetV2
- EfficientNet-B0

Key Results
-----------
- Best test accuracy: EfficientNet-B0 → 88.11%
- Most parameter-efficient model with strong performance: MobileNetV2
- VGG-16 training failed due to spatial dimension mismatch in the architecture

Technology Stack
----------------
- Python
- PyTorch
- Google Colab

Project Structure
-----------------
notebooks/     → Jupyter/Colab notebooks containing model implementation and training
report/        → Final research report (PDF)

Highlights
----------
- Application of transfer learning improves final accuracy by approximately 7 percentage points compared to training from scratch.
- Classification of "cat" and "dog" classes remains among the most challenging categories across all models.
- EfficientNet-B0 achieves the highest accuracy while maintaining a favorable parameter count.

Author
------
Subham Nayak
