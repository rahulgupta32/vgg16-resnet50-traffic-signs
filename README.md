# vgg16-resnet50-traffic-signs
Deep Learning Fusion Ensemble for Enhanced Traffic Sign Detection Using the ICTS Dataset


### Project Overview
This project aims to enhance traffic sign detection using a deep learning fusion ensemble approach. The architecture combines VGG16 and ResNet50 to leverage the strengths of both models, improving accuracy in recognizing traffic signs.

### Tools & Technologies Used
1. Programming Language: Python
2. Deep Learning Frameworks: TensorFlow, Keras
3. Models Used: VGG16, ResNet50 (Fusion Ensemble)
4. Data Processing: NumPy, Pandas, OpenCV
5. Visualization: Matplotlib, Seaborn
6. Deployment (Optional): Azure Machine Learning, FastAPI


### Dataset
The dataset used in this project can be downloaded from Google Drive: "https://drive.google.com/file/d/1n5uDIKwxy6Wd7hRMX86EiWgi0QW_gBcN/view?usp=sharing"
Sample Image of the dataset: ![Trafic signs images icts](https://github.com/user-attachments/assets/80060551-8ba3-4640-9f69-1a2a9efa627b)



### Methodology
The methodology involves a deep learning-based fusion ensemble to enhance traffic sign detection and recognition using the ICTS dataset. The project leverages the complementary strengths of two pre-trained convolutional neural network (CNN) models, VGG16 and ResNet50, to improve detection accuracy and generalization.

### Data Preprocessing:

Image normalization, resizing, and augmentation to enhance model performance and prevent overfitting.

### Model Architecture:

1. VGG16 and ResNet50 are combined in an ensemble to extract robust features from the input images.

2. Fusion occurs by merging the feature maps from both models, creating a hybrid feature representation.

### Training and Optimization:

1. The fused model is trained on the ICTS dataset using cross-entropy loss and optimized using advanced optimizers like Adam.

2. Hyperparameters such as learning rate, batch size, and epochs are carefully tuned.

### Evaluation Metrics:

The model is evaluated using metrics like Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC Curve to measure its performance on test data.





The Proposed model:
![vgg16_resnet50_model_methodology](https://github.com/user-attachments/assets/d9aa69e3-213c-47b9-b442-96af36602782)

Internal Model Structure:
![internal_model_structure](https://github.com/user-attachments/assets/fa1c8a3f-8a17-4e55-a14f-1d3607a44f5d)


The Evaluation Metrices:


Accuracy Curve: ![accuracy_curve](https://github.com/user-attachments/assets/6e9b6717-76c4-41d9-ba94-c5e149a45c04)



Loss Curve: ![loss_curve](https://github.com/user-attachments/assets/e8cd10eb-4643-4bfc-bdd9-0153cb35ac16)



Confusion Matrix: ![confusion_matrix](https://github.com/user-attachments/assets/fac131b0-d5e0-417e-88d2-3d61c29de524)



ROC Curve: ![roc_curve](https://github.com/user-attachments/assets/7f6f788c-f472-4af6-9777-9ebee965fdc0)



