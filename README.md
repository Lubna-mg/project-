# 👁️ بصيرة | Basira – AI-Based Autism Detection

**Basira** is a smart diagnostic system that leverages **AI** and **eye-tracking data** to enable early detection of **Autism Spectrum Disorder (ASD)** in children. By analyzing visual patterns through scanpath images and gaze metrics, Basira supports medical professionals and parents in making more accurate, timely decisions.

> 🏆 1nd Place Winner – Most Voted Graduation Project – College of Computer Science 2025
> 🏆 2nd Place Winner – Ebtekar Innovation Incubator  


---

## 💡 About the Project

 is an innovative diagnostic platform that integrates eye-tracking technology with AI-powered data analysis to support the early detection of Autism Spectrum Disorder (ASD) in children.

The system is designed to analyze both visual scanpath images and structured numerical eye-tracking metrics, using a combination of deep learning and machine learning techniques to identify patterns indicative of ASD.

Unlike traditional diagnostic approaches, Basira offers a fast, scalable, empowering healthcare professionals and caregivers with a tool that improves diagnostic confidence .

---

## 🧠 Implementation Overview

### 🔬 Image-Based Deep Learning – VGG16
- **Architecture**: VGG16 with transfer learning.
- **Dataset**: Eye-tracking scanpath images (ASD vs. Non-ASD).
- **Preprocessing**: Resize, normalization, data augmentation.
- **Performance**:
  - Accuracy: `96.53%`
  - Sensitivity: `97.8%`
  - Specificity: `94.3%`

### 📊 Numeric-Based Machine Learning – Random Forest
- **Dataset**: Eye metrics (Pupil Diameter L/R, Tracking Ratio).
- **Preprocessing**: Feature selection, SMOTE, normalization.
- **Performance**:
  - Accuracy: `96.36%`
  - Balanced precision/recall.

---

## 🛠️ Technologies & Tools

| Category       | Tools & Libraries                                             |
|----------------|--------------------------------------------------------------|
| Programming    | Python                                                       |
| Deep Learning  | TensorFlow, Keras (VGG16), Transfer Learning                 |
| ML Algorithms  | Random Forest (Scikit-learn)                                 |
| Image Analysis | OpenCV, PIL                                                  |
| Preprocessing  | Pandas, NumPy, StandardScaler, SMOTE                         |
| Evaluation     | Matplotlib, Seaborn, Confusion Matrix, F1-score              |

---

## 🔬 Results Comparison

| Model       | Accuracy | Sensitivity | Specificity | Data Type       |
|-------------|----------|-------------|-------------|-----------------|
| VGG16       | 96.53%   | 97.8%       | 94.3%       | Eye Images      |
| RandomForest| 96.36%   | Balanced    | Balanced    | Eye Metrics     |

> Compared to prior models (GoogleNet, ResNet-18, SVM), Basira achieved **competitive or superior performance** using carefully preprocessed data and robust modeling.

---

## 🔐 Code & Dataset Access

This project is part of a protected academic and research effort.  
📁 **Source code and datasets are not publicly available** to preserve intellectual property.

> 📩 For demo access, academic collaboration, or partnerships: please contact the developer.

---

## 📬 Contact

- 📧 Email: [lubna.mg@hotmail.com](mailto:lubna.mg@hotmail.com)  
- 💼 LinkedIn: [Lubna Alghamdi](https://www.linkedin.com/in/lubna-al-ghamdi-16150b29b)  
- 🌐 Portfolio: [Your Portfolio Link Here](https://yourportfolio.com)

---

© 2025 Lubna Alghamdi. All rights reserved.
