
# Skin Cancer Classification using Hybrid Deep Learning

This project classifies dermoscopy images of skin lesions into 9 different diagnostic categories using transfer learning. It uses **EfficientNet-B0** as a base model and explores MobileNetV2 as an alternative. The dataset used is the **HAM10000** ("Human Against Machine") dataset.

---

## Project Summary

- **Dataset:** [HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- **Model:** Transfer learning with EfficientNet-B0 and MobileNetV2
- **Task:** Multi-class image classification (9 skin cancer classes)
- **Goal:** Predict lesion types from dermoscopic images to assist in early diagnosis of skin cancers

---

##  Skin Lesion Categories

1. **Actinic keratoses**
2. **Basal cell carcinoma**
3. **Benign keratosis-like lesions**
4. **Dermatofibroma**
5. **Melanocytic nevi**
6. **Melanoma**
7. **Vascular lesions**
8. **Squamous cell carcinoma**
9. **Others / Unclassified**

---

## Tools & Frameworks

- Python
- TensorFlow / Keras
- EfficientNet / MobileNetV2 (pretrained)
- OpenCV, NumPy, pandas
- scikit-learn (metrics)
- Matplotlib & seaborn (visualization)

---

##  Techniques Used

- **Transfer Learning** with EfficientNetB0
- **Image Preprocessing**: Resizing to 224x224, normalization
- **Data Augmentation**: Rotation, flipping, contrast/brightness shifts
- **Evaluation Metrics**: Accuracy, F1 Score, Confusion Matrix
- **Submission Generator**: Outputs `submission.csv` in Kaggle format

---

## Future Improvements

- Integrate Grad-CAM for model explainability
- Add ensemble learning or test-time augmentation
- Deploy model with Streamlit or Flask for demo use

---

