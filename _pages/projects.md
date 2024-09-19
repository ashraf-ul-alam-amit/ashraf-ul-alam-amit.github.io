---
title: "Projects"
permalink: /projects/
---

---

## **Cycle Thief Detection from Live CCTV Footage using YOLOv5 and DeepSORT [[Project]](https://github.com/ashraf-ul-alam-amit/cycle_theif)**  
### *Ashraf Ul Alam, Soumit Das*

This project involves the development of a real-time cycle thief detection system utilizing advanced technologies. YOLOv5 is employed for object detection, enabling the system to identify cycles in live CCTV footage. DeepSORT is integrated for tracking the detected objects across frames, while the KD-Tree algorithm enhances the efficiency of nearest neighbor searches. Additionally, the Face_Matcher tool is used for facial recognition, further aiding in the identification of suspects. Together, these components create a robust solution for monitoring and addressing cycle theft in real-time.

---

## **KD-UDA: Knowledge Distillation-based Unsupervised Domain Adaptation for Improved Medical Image Segmentation [[Project]](https://github.com/ashraf-ul-alam-amit/KD-UDA)**  
### *Ashraf Ul Alam, S. M. Mahedy Hasan*

The KD-UDA project focuses on enhancing segmentation performance across unseen target domains using knowledge distillation for unsupervised domain adaptation. The primary goal is to adapt models to new domains without requiring labeled data from these domains. This is achieved by transferring knowledge from a model trained on the source domain to a target domain model using knowledge distillation. The approach incorporates source loss and domain shift loss with Kullback-Leibler (KL) divergence to address domain shift issues. The framework's effectiveness is evaluated on 2D datasets (Drishti-GS, RIM-ONE-R3, REFUGE Source-1, and REFUGE Source-2) for retinal images and a 3D dataset (BraTS2021) for MRI scans. In both scenarios, the framework significantly improves segmentation performance on target datasets.

---

## **Deepfake Image Detection using VGG16 and Channel Attention [[Project]](https://github.com/ashraf-ul-alam-amit/Deepfake-Image-Detection)**  
### *Ashraf Ul Alam, Sudipta Progga Islam*

This project focuses on detecting deepfake images using the [140k Real and Fake Faces](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces/data) dataset from Kaggle. The VGG16 model, known for its deep architecture, was employed as the primary feature extractor. To enhance performance, a **channel attention mechanism** was introduced, allowing the model to prioritize relevant feature channels while reducing the impact of less useful ones. This resulted in a significant improvement in classification accuracy. Additionally, an **ablation study** was conducted using ResNet50, demonstrating how attention mechanisms improve feature representation. The final model achieved a high accuracy of **99.80%** with [VGG16 and channel attention](https://github.com/ashraf-ul-alam-amit/Deepfake-Image-Detection/blob/master/vgg_channel-attention.ipynb), making it an effective solution for detecting deepfake images.

---
## **Chronic Kidney Disease Prediction using Machine Learning [[Project]](https://github.com/ashraf-ul-alam-amit/CKD)**  
### *Ashraf Ul Alam*

In this project, a machine learning model was developed to predict Chronic Kidney Disease (CKD) at an early stage. The process included comprehensive exploratory data analysis and feature engineering to optimize model accuracy. A user-friendly prediction tool was then created, featuring a Flask API for deployment and a web interface designed with HTML and CSS. This tool facilitates early CKD detection, providing users with a practical solution for managing their health.

---

## **Maternal and Child Health Care [[Project]](https://github.com/ashraf-ul-alam-amit/Maternal_Care)**  
### *Ashraf Ul Alam, Sudipta Progga Islam*

This initiative involved creating a comprehensive Maternal and Child Health Care website designed to support expecting mothers with tools for due date calculation and immunization schedules. The site features personalized SMS and email notifications, as well as a query posting function to facilitate communication with healthcare specialists. Additionally, a mobile app was developed using Android Studio and Firebase, mirroring the website’s features. This project aims to enhance prenatal and postnatal care by providing a supportive online platform for mothers.

---

## **Cardiotocogram Data Analysis for Fetal Health Classification Using Machine Learning [[Project]](https://github.com/ashraf-ul-alam-amit/fetal_health) [[Slide]](https://github.com/ashraf-ul-alam-amit/fetal_health/blob/master/fetal_health.pdf)**  
### *Ashraf Ul Alam*

This project aims to classify fetal health status using machine learning models applied to Cardiotocogram (CTG) data. The dataset consists of 2,126 records with 21 features extracted from CTG exams, categorized into three classes: Normal, Suspect, and Pathological. Models like Random Forest, K-Nearest Neighbors, and Gradient Boosting were trained on the preprocessed dataset. Feature selection, data standardization, and SMOTE were employed to improve model performance. Random Forest achieved the highest accuracy of 98.47%. This project showcases how machine learning can assist in automating and improving fetal health assessment.

---




