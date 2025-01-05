# DS340_Final_Project

**Weather Classification and Clothing Recommendation System**

This project bridges the gap between weather forecasting and actionable advice by classifying weather conditions from images and recommending suitable clothing based on detected weather patterns.

**Key Features**

Advanced Deep Learning Models: Utilizes transfer learning with pre-trained models like ResNet50, MobileNet, and VGG19.

Custom Image Processing Pipeline: Preprocessed and augmented weather image data to enhance generalization and handle class imbalance.

Practical Applications: Provides actionable clothing recommendations based on classified weather conditions.

**Methodology**

Dataset: A curated dataset of weather images representing 11 unique conditions, including snow, rain, and sandstorms.

Model Development:

Baseline: Custom CNN achieving ~66% accuracy.
Enhanced: ResNet50 fine-tuned for superior performance (~83% accuracy).
Evaluation: Metrics include accuracy, precision, recall, and F1-score, addressing challenges like imbalanced categories.

**Results**

ResNet50 outperformed other models, demonstrating robust generalization and minimal overfitting.
Extended applications included testing on external datasets and generating clothing suggestions for various weather scenarios.

**Future Directions**

Expand dataset diversity and explore newer architectures like Vision Transformers.
Develop real-time prediction capabilities for improved usability.
