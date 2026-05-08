
 **Hybrid Deep Learning and Machine Learning Framework for Forest Fire Detection**

This project presents a hybrid artificial intelligence framework for intelligent forest fire detection using deep learning-based feature extraction and traditional machine learning classifiers. The system combines multiple pretrained CNN architectures with machine learning algorithms to accurately classify wildfire and non-wildfire images.

**The proposed framework achieved high wildfire detection accuracy, with DenseNet121 + SVM achieving the best performance of 97.98%.**

 Features
- Hybrid CNN + Machine Learning framework
- Real-time wildfire detection capability
- Comparative analysis of 32 hybrid models
- Deep feature extraction using pretrained CNNs
- Performance evaluation using Accuracy, Precision, Recall, and F1-Score
- Heatmap visualization and confusion matrix analysis
- Lightweight and scalable wildfire monitoring approach

---
  **Deep Learning Models Used**
- DenseNet121
- InceptionV3
- Xception
- MobileNetV2
- MobileNetV3
- EfficientNetB5
- ResNet50
- VGG19

---
** Machine Learning Classifiers**
- Support Vector Machine (SVM)
- Random Forest
- Decision Tree
- Naïve Bayes

---

**Best Performing Models**

| Model Combination | Accuracy |
|-------------------|-----------|
| DenseNet121 + SVM | 97.98% |
| InceptionV3 + SVM | 97.87% |
| DenseNet121 + Random Forest | 96.37% |
| Xception + Random Forest | 95.94% |

---

 **Dataset**
The dataset contains 11034 wildfire and non-wildfire images used for classification and performance evaluation.
Data set link - https://www.kaggle.com/datasets/cristiancristancho/forest-fire-image-dataset

##  Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- OpenCV
- NumPy
- Matplotlib
- Seaborn


##  Results
The proposed hybrid framework demonstrated excellent wildfire classification performance. **SVM-based hybrid models** consistently achieved superior accuracy and reliability compared to other classifiers.

Key observations:
- DenseNet121 and InceptionV3 extracted highly discriminative wildfire features.
- SVM achieved the best overall classification performance.
- Random Forest provided stable and robust results.
- Naïve Bayes showed inconsistent performance with some feature extractors.


## Visualizations Included
- Confusion Matrices
- Accuracy Heatmaps
- Precision, Recall, and F1-Score Comparisons
- Feature Map Visualizations
- Accuracy Comparison Graphs

---

##  Future Enhancements
- Integration with IoT sensors and satellite imagery
- Real-time wildfire monitoring system
- Explainable AI using SHAP and LIME
- Lightweight deployment on edge devices
- Fire spread prediction and severity estimation

---

##  Conclusion
The project demonstrates that hybrid CNN–ML approaches significantly improve wildfire detection performance. DenseNet121 + SVM emerged as the most effective model, achieving highly accurate and reliable wildfire classification suitable for real-world early warning systems.

---

## 👨‍💻 Author
Anjali Jha

---

##  If you found this project useful, consider giving it a star! ⭐
```
