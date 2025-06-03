# **Cancer Cell Classification with CNN**

![Project Logo](https://storage.googleapis.com/kaggle-datasets-images/1306086/2175623/b956bf851fc7b05876bf41af7fd4cb55/dataset-cover.jpg?t=2021-07-21-08-55-43)

## **Project Description**

This project leverages **Convolutional Neural Networks (CNNs)** to classify **Acute Lymphoblastic Leukemia (ALL) and Hematopoietic (HEM) cells** from microscopic images. With an **82.21% test accuracy**, the model demonstrates strong potential for assisting medical professionals in leukemia diagnosis.

## **Dataset Overview**

We utilize the **C-NMC Leukemia Dataset**, a well-known dataset from Kaggle designed for **medical imaging research**.  
[Dataset Link](https://www.kaggle.com/datasets/avk256/cnmc-leukemia)

### **Dataset Summary**

- **Acute Lymphoblastic Leukemia (ALL)** constitutes approximately **25% of pediatric cancers**.
- Identifying **immature leukemic blasts** from normal cells is challenging due to morphological similarities.

#### **Dataset Composition**

📌 **Training Set**

- Total Subjects: **73**
  - **47** ALL (cancer)
  - **26** Normal
- Total Cell Images: **10,661**
  - **7,272** ALL (cancer)
  - **3,389** Normal

📌 **Preliminary Test Set**

- Total Subjects: **28**
  - **13** ALL (cancer)
  - **15** Normal
- Total Cell Images: **1,867**
  - **1,219** ALL (cancer)
  - **648** Normal

📌 **Final Test Set**

- Total Subjects: **17**
  - **9** ALL (cancer)
  - **8** Normal
- Total Cell Images: **2,586**

---

## **Key Features**

- ✅ **Deep Learning Model (CNN)** for robust image classification
- ✅ **Data Augmentation** to improve model generalization
- ✅ **Confusion Matrix & ROC Curve** for model performance evaluation
- ✅ **Integration with Medical Imaging Datasets** for real-world applications

## **Technology Stack**

### **Machine Learning**

- TensorFlow / Keras
- OpenCV (Image Preprocessing)
- NumPy & Pandas

### **Development & Cloud Tools**

- Python 3.x
- Jupyter Notebook / VS Code

## **Results & Insights**

📌 **Confusion Matrix** reveals **2,078 correctly classified ALL images** & **777 correctly classified HEM images**  
📌 **ROC Curve Analysis** confirms strong model differentiation between classes  
📌 **Overall Model Test Accuracy: 82.21%**, making it highly suitable for medical diagnostics

## **Future Improvements**

🔹 **Integrate transfer learning** for enhanced accuracy  
🔹 **Expand dataset** to further improve generalization  
🔹 **Optimize hyperparameters** for better performance

## **Publications Using This Dataset**

- **GCTI-SN:** Stain Normalization for Microscopic Images ([DOI](https://doi.org/10.1016/j.media.2020.101788))
- **SD-Layer:** Stain Deconvolution for CNNs ([DOI](https://doi.org/10.1007/978-3-319-66179-7_50))
- **Deep Belief Networks for Cell Segmentation** ([ICVGIP Conference](https://doi.org/10.7937/tcia.2019.dc64i46r))

## **Contributors**

- **Lucky** (Lead Developer)
- Open for contributions! Submit **pull requests** or issues 🚀

## **License**

Licensed under **MIT License**—feel free to modify and improve.

### **Acknowledgments**

Special thanks to **medical imaging researchers** and open-source datasets for supporting leukemia classification advancements.
