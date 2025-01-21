# DS340_Final_Project: Weather Image Classification and Clothing Recommendation System

## Overview
This project bridges the gap between weather forecasting and actionable advice by:
- Classifying weather conditions from images.
- Recommending suitable clothing based on detected weather patterns.

The system leverages advanced deep learning techniques to provide accurate weather classifications and practical recommendations.

---

## Key Features
- **Advanced Deep Learning Models:**
  - Utilizes transfer learning with pre-trained models such as ResNet50, MobileNet, and VGG19.
- **Custom Image Processing Pipeline:**
  - Preprocessed and augmented weather image data to enhance generalization and handle class imbalance.
- **Practical Applications:**
  - Provides actionable clothing recommendations based on classified weather conditions.

---

## Methodology

### Dataset
- Curated dataset of weather images representing **11 unique conditions**, including:
  - Snow, Rain, Sandstorms, and more.

### Model Development
1. **Baseline Model:**
   - Custom Convolutional Neural Network (CNN) achieving ~66% accuracy.
2. **Enhanced Model:**
   - Fine-tuned **ResNet50**, achieving superior performance (~83% accuracy).
3. **Evaluation:**
   - Metrics include:
     - Accuracy
     - Precision
     - Recall
     - F1-score
   - Addressed challenges like imbalanced categories through data augmentation and weighted loss functions.

---

## Results
- **ResNet50** outperformed other models, demonstrating:
  - Robust generalization.
  - Minimal overfitting.
- Extended applications included:
  - Testing on external datasets.
  - Generating clothing recommendations for various weather scenarios.

---

## Future Directions
- Expand dataset diversity to include more weather conditions and geographic regions.
- Explore newer architectures like **Vision Transformers** for improved accuracy.
- Develop real-time prediction capabilities for enhanced usability.

---

## Tools and Technologies
- **Deep Learning Models:** ResNet50, MobileNet, VGG19, Custom CNN
- **Programming Language:** Python
- **Libraries and Frameworks:** TensorFlow, Keras, OpenCV
- **Data Visualization:** Matplotlib, Seaborn
- **Image Augmentation:** TensorFlow's `ImageDataGenerator`

---

