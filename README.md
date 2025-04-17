his repository contains the implementation of my thesis:
"Optimizing Multi-Scale CNN with Attention Mechanisms for Automated AMD Diagnosis from Retinal OCT Images."

📌 Overview
This work proposes a Feature Pyramid Network (FPN)-based CNN architecture enhanced with attention mechanisms (Soft Attention, Channel Attention, SE block) to improve automated diagnosis of Age-related Macular Degeneration (AMD) using retinal OCT images.

📊 Highlights
📈 Achieved 96% accuracy on the NEH dataset — a 4% improvement over the referenced paper.

⚙️ Used pre-trained CNN backbones like VGG16, ResNet50, Xception, DenseNet121, and EfficientNet-B0.

🧩 Incorporated attention mechanisms to enhance feature learning.

🗂️ Tested across multiple datasets (NEH, UCSD, etc.) for generalization.

🧠 Visualized important features using Grad-CAM++ for interpretability.

🛠️ Key Features
✅ FPN with multi-scale feature fusion

✅ Lightweight architecture with fewer parameters

✅ Explainable AI via Grad-CAM++

✅ Comparative analysis with referenced models

📁 Dataset
The project uses publicly available NEH and UCSD OCT datasets.

Dataset split into training, validation, and test folders.

🧪 Results

Model	Accuracy	Parameters
FPN + VGG16	96%	16.1M
Base Paper	92%	21.6M
📦 Requirements
Python ≥ 3.8

TensorFlow / Keras

OpenCV, NumPy, Matplotlib

scikit-learn
