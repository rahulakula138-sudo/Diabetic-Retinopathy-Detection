**📘 Diabetic Retinopathy Detection Using Deep Learning**

A Convolutional Neural Network (CNN)–Based Approach

**📄 Overview**

Diabetic Retinopathy (DR) is a diabetes-induced eye disease that damages retinal blood vessels and can lead to irreversible blindness if not detected early. Manual examination of retinal fundus images is time-consuming, expensive, and prone to human error.
This project leverages Deep Learning (CNN) to automate the detection and grading of Diabetic Retinopathy using retinal fundus images.

The system processes retina images, classifies them into DR stages, and assists clinicians in early diagnosis and treatment planning.

**🧠 Key Features**

Automated detection of Diabetic Retinopathy using Convolutional Neural Networks

5-class and binary classification support (No DR, Mild, Moderate, Severe, Proliferative DR)

Data preprocessing & augmentation for improved model generalization

Training, validation, and testing pipeline (75-15-15 split)

Achieved ~93% accuracy, with strong sensitivity and specificity

Supports new image prediction through a trained model

**📊 System Workflow**

**1. Input Images**

Retina fundus images obtained from the APTOS 2019 Blindness Detection dataset.

**2. Preprocessing**

Resizing to 224×224

Noise removal

Normalization (pixel rescaling)

Data Augmentation: zoom, shear, flip (horizontal/vertical)

**3. Deep Learning Model**

A custom CNN architecture including:

Convolution Layers

Max-Pooling

Dropout

Dense layers (Sigmoid/Softmax)

**4. Classification Output**

Model predicts:

Binary classification: DR / No DR
or

Multi-class classification (optional): No DR, Mild, Moderate, Severe, Proliferative DR

**🛠️ Technologies Used**

Python 3

TensorFlow / Keras

NumPy, Pandas, Matplotlib

OpenCV

Jupyter Notebook / Google Colab

**Understanding Diabetic Retinopathy**
Non-Proliferative DR (NPDR)

Microaneurysms

Hemorrhages

Hard/Soft exudates

Retinal swelling

Proliferative DR (PDR)

Growth of fragile, abnormal blood vessels

Vitreous hemorrhage

Risk of retinal detachment

The system detects these visual patterns using deep learning.

