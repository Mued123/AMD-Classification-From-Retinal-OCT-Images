# AMD-Classification-From-Retinal-OCT-Images
This repository contains the implementation of my thesis project titled:
"Optimizing Multi-Scale CNN with Attention Mechanisms for Automated AMD Diagnosis from Retinal OCT Images."

The study proposes an enhanced FPN-based architecture using various CNN backbones (VGG16, ResNet50, DenseNet121, etc.) integrated with attention modules (e.g., Soft Attention, Squeeze-and-Excitation) to improve classification performance on retinal OCT images. The model is evaluated on multiple datasets (NEH, UCSD), achieving high accuracy and demonstrating strong generalization capability with reduced parameter count.

🔬 Key Features:
Multi-scale feature extraction using Feature Pyramid Networks (FPN)

Integration of attention mechanisms for enhanced focus on retinal pathology

Experiments conducted on NEH, UCSD, and other public OCT datasets

Visualization with Grad-CAM++ to highlight important regions

Comparative analysis with baseline and state-of-the-art models

📈 Achievements:
Achieved up to 96% accuracy on the UCSD dataset

Outperformed the base paper with significantly fewer parameters

Demonstrated strong generalization across diverse datasets

🚀 Tech Stack:
TensorFlow / Keras

Python

Jupyter Notebooks

Matplotlib, Seaborn for visualizations

📂 Structure:
models/ – Backbone models with FPN and attention

notebooks/ – Training, evaluation, and visualization

data/ – Data loading and preprocessing

results/ – Performance metrics and figures

README.md – Project overview and usage
