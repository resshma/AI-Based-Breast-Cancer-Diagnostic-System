# AI-Based-Breast-Cancer-Diagnostic-System
Using deep learning models to accurately classify breast cancer from ultrasound images, improving early and non-invasive diagnosis.

Outcomes:

The custom CNN performed best with 80.78% accuracy and good generalization.
VGG16 was close behind at 80.22%, benefiting from transfer learning.
EfficientNetB0 lagged at 55.56%, likely due to limited fine-tuning and dataset fit.
Data augmentation and transfer learning were crucial in improving results and reducing overfitting.
The study highlights how tailored model design matters for specific datasets.

Files:
Dataset: Public Ultrasound Breast Images for Breast Cancer Detection
Code & Models: (Links available if needed)
Visualizations: Accuracy and loss curves, ROC curves, confusion matrices
Training Notebooks: Google Colab notebooks documenting the entire process
Tools Used:

TensorFlow & Keras for building and training models
Google Colab for running GPU-accelerated experiments
Python for data prep and modeling
Matplotlib & Seaborn for visualizations
Data augmentation tools like Keras ImageDataGenerator
Pre-trained ImageNet weights for transfer learning in VGG16 and EfficientNetB0
