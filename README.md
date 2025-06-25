# AI-Based-Breast-Cancer-Diagnostic-System
Using deep learning models to accurately classify breast cancer from ultrasound images, improving early and non-invasive diagnosis.


* Dataset:  3000+ Ultrasound breast images labeled benign/malignant, augmented with rotation, zoom.
* Models Evaluated: Custom CNN, VGG16, EfficientNetB0.

Training: Binary cross-entropy loss, Adam optimizer, early stopping, 20 epochs max, batch size 32, 20% validation split.

 Evaluation Metrics: Validation accuracy, precision, recall, F1-score, confusion matrix, ROC-AUC.

* Outcomes:

 - The custom CNN performed best with 80.78% accuracy and good generalization.
 - VGG16 was close behind at 80.22%, benefiting from transfer learning.
 - EfficientNetB0 lagged at 55.56%, likely due to limited fine-tuning and dataset fit.

* Files:
Dataset: Public Ultrasound Breast Images for Breast Cancer Detection
Code & Models: [Your Link Here] (file:///Users/reshma/Downloads/NNDL_Project_File%20(2).pdf)
Visualizations: Accuracy and loss curves, ROC curves, confusion matrices
Training Notebooks: Google Colab notebooks documenting the entire process
Tools Used:

TensorFlow & Keras for building and training models
Google Colab for running GPU-accelerated experiments
Python for data prep and modeling
Matplotlib & Seaborn for visualizations
Data augmentation tools like Keras ImageDataGenerator
Pre-trained ImageNet weights for transfer learning in VGG16 and EfficientNetB0
