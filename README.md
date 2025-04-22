**Skin Map : A Multimodal Approach To Detect And Explain Skin Cancer**

**Project Overview**
This project aims to develop an AI-based system for skin cancer detection using deep learning models. The system classifies skin lesions as benign or malignant using dermoscopic images and integrates patient metadata (e.g., age, gender, lesion location) to improve diagnostic accuracy. The models used include ResNet101 for multiclass classification and ResNeSt101 for binary classification. The system also incorporates Grad-CAM to visualize and explain the model's decision-making process, ensuring transparency and interpretability.

**Key Features**
Multiclass classification of skin lesions (7 types) using ResNet101.

Binary classification of lesions as benign or malignant using ResNeSt101.

Grad-CAM visualizations to explain model predictions.

Integration of patient metadata for improved prediction accuracy.

Built with PyTorch for deep learning model development.

**Technologies Used**
Programming Language: Python 3.x

Deep Learning Framework: PyTorch

Data Handling: Pandas, NumPy

Image Processing: OpenCV, PIL

Explainability: Grad-CAM

Visualization: Matplotlib, Seaborn

GPU: CUDA (for NVIDIA GPUs)

**Dataset**
The models were trained using the HAM10000 dataset and ISIC 2020 Challenge dataset. These datasets contain high-resolution dermoscopic images annotated with skin lesion types and clinical metadata.

-> HAM10000

-> ISIC 2020

