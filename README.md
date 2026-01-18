# Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision

This project focuses on automated brain tumor detection and classification using Deep Learning and Computer Vision techniques applied to MRI images. A VGG16-based Convolutional Neural Network (CNN) is trained to classify MRI scans into four categories:

* Glioma

* Meningioma

* Pituitary tumor

* No Tumor

The system is capable of:

* Learning discriminative features from MRI images
* Accurately classifying tumor types
* Providing prediction confidence scores
* Assisting medical professionals as a decision-support tool, not a replacement

# Dataset
[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?resource=download)

# Project Directory

```bash
brain-project/
│
├── training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
│
├── testing/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
│
├── brain_tumour_detection_using_deep_learning.ipynb
└── README.md

```

# Tools used

* Python (3.10 version)

* TensorFlow / Keras

* VGG16 (Transfer Learning)

* NumPy

* Matplotlib

* Seaborn

* Scikit-learn

* OpenCV / PIL

# SETUP Instructions

* Clone the repository
```bash
git clone https://github.com/MohamedZakkaria2004/Brain-Tumor-Detection.git
cd Brain-Tumor-Detection
```
* Open Notebook
```bash
jupyter notebook
```
* Open
```bash
Brain_Tumor_Detection_Model.ipynb
```
* Run the Cells Sequentially

# Model Evaluation Metrics
The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC Curve & AUC

# Sample Output

The system displays:

* Input MRI image

* Predicted class (tumor type / no tumor)

* Confidence score

<img width="584" height="614" alt="Screenshot 2026-01-18 204336" src="https://github.com/user-attachments/assets/0c7d1351-9789-40e8-b554-5fdc8f376db2" />

<img width="537" height="614" alt="Screenshot 2026-01-18 204344" src="https://github.com/user-attachments/assets/9a455c1b-95ef-4a8d-8a65-efc8fff4027f" />
