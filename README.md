# PRCP--1001--RiceLeaf-disease-detection
Rice Leaf Disease Detection using Deep Learning (CNN). The project classifies rice leaf images into three categories: Leaf Smut, Brown Spot, and Bacterial Leaf Blight. Helps in early identification of plant diseases for improved crop yield.
#  Rice Leaf Disease Detection using CNN

This project uses **Deep Learning (Convolutional Neural Networks)** to classify rice leaf images into different disease categories. Early detection of rice leaf diseases helps farmers improve crop yield and prevent large-scale damage.  

---

##  Project Overview
- Built a **CNN model** to detect rice leaf diseases from images.  
- Dataset consists of three major rice diseases:  
  - **Leaf Blast**  
  - **Bacterial Blight**  
  - **Brown Spot**  
- Applied **data preprocessing, augmentation, and model training** for robust classification.  
- Evaluated performance with accuracy and loss graphs.  

---

## Dataset Information
- Images of rice leaves affected by three major diseases.  
- Preprocessed using **OpenCV & Keras ImageDataGenerator**.  
- Dataset split into **training and testing sets**.  
- Images converted to arrays and normalized for CNN model input.  

---

##  Technologies Used
- Python   
- OpenCV – Image preprocessing  
- TensorFlow / Keras – Deep Learning model  
- NumPy, Pandas – Data handling  
- Matplotlib – Visualization  

---

##  Model Architecture
The CNN model consists of:  
- Convolutional Layers (feature extraction)  
- MaxPooling Layers (dimensionality reduction)  
- Flatten Layer (conversion to 1D)  
- Dense Layers (classification)  
- Softmax activation for final prediction  

---

##  Results
- The model achieved **high accuracy** in classifying rice leaf diseases.  
- Training & validation accuracy/loss plotted to evaluate model performance.  
- Most influential factors: disease type and leaf texture patterns.  

---


