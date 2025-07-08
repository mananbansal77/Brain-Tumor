# 🧠 Brain Tumor Detection using Deep Learning

This project focuses on detecting brain tumors from MRI images using deep learning techniques. The goal is to assist radiologists and medical professionals by providing an efficient and accurate diagnostic tool that reduces manual effort and enhances early detection.

---

## 📌 Project Objective

To create a reliable classification model that identifies and categorizes brain tumors in MRI scans into the following categories:

- **Glioma**
- **Meningioma**
- **Pituitary Tumor**
- **No Tumor**

---

## 📂 Dataset

- **Source**: [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets)
- **Format**: JPEG images
- **Categories**: Tumorous and Non-Tumorous
- Images are pre-labeled and suitable for supervised learning.

---

## 🛠️ Tech Stack

- **Language**: Python 3.x  
- **Libraries**:
  - NumPy, Pandas
  - OpenCV
  - Matplotlib, Seaborn
  - TensorFlow / Keras
  - Scikit-learn

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Resize all images to a fixed size (e.g., 150x150).
- Normalize pixel values between 0 and 1.
- Convert to grayscale (if needed).
- Perform data augmentation (rotation, flipping, zooming).

### 2. CNN Model Architecture
- Convolutional Layers with ReLU activation
- MaxPooling layers for dimensionality reduction
- Dense layers with Dropout to avoid overfitting
- Final layer with Softmax activation for classification

### 3. Training & Evaluation
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
- Tools like confusion matrix and ROC curves are used for validation

---

## 📈 Results

- **Training Accuracy**: ~98%
- **Validation Accuracy**: ~95%
- Model performs well across all four categories
- Effectively distinguishes between tumor types

---

## 💡 Future Scope

- Extend to 3D volumetric MRI analysis
- Integration with real-time clinical tools
- Implement explainable AI (Grad-CAM visualizations)
- Incorporate patient history and metadata for improved accuracy

---

## 🧪 Research Significance

This project represents the growing potential of AI in medical diagnostics. It also highlights key aspects of responsible AI practices, such as:

- Data ethics
- Fairness and bias mitigation
- Interpretability of predictions
- Privacy-preserving model design

---

## 👨‍🎓 Author

**Manan Bansal**  
B.Tech, Graphic Era University  
📧 bansalmanan007@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/manan-bansal-7a71a7270/)  
💻 [GitHub](https://github.com/mananbansal77)

---

## 📜 License

This project is open-source under the **MIT License**.

---

## 🙌 Acknowledgements

- Guided by faculty at **Graphic Era University**
- Dataset curated from **Kaggle**
- Inspired by real-world applications of AI in healthcare
