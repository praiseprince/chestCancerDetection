# Chest Cancer Detection

This project focuses on detecting chest cancer using machine learning and deep learning techniques. The dataset consists of chest CT-scan images categorized into four classes: Adenocarcinoma, Large-cell carcinoma, Squamous cell carcinoma, and Normal.

## Dataset
The dataset contains images in JPG or PNG format and is organized into three folders: train, test, and valid. The training set comprises 70% of the data, the testing set 20%, and the validation set 10%.

- **Adenocarcinoma**: Lung adenocarcinoma, the most common form of lung cancer.
- **Large-cell carcinoma**: A type of lung cancer that grows and spreads quickly.
- **Squamous cell carcinoma**: Found centrally in the lung and generally linked to smoking.
- **Normal**: CT-scan images of normal lung tissue.

**Dataset Source**: [Chest CT-Scan images Dataset](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)

## Model Architecture
The project utilizes several pre-trained models, including EfficientNetB3, ResNet50, and InceptionV3, for feature extraction. A final ensemble model is created by averaging the predictions from these models.

- **EfficientNetB3**: Achieved a train accuracy of 99.84% and a test accuracy of 84.76%.
- **ResNet50**: Achieved a train accuracy of 99.84% and a test accuracy of 79.05%.
- **InceptionV3**: Achieved a train accuracy of 93.96% and a test accuracy of 44.13%.
- **Ensemble Model**: Achieved a test accuracy of 84.76%.

## Metrics and Evaluation
- **Confusion Matrix**: Shows the classification results for each class.
- **Classification Report**: Provides precision, recall, F1-score, and support for each class.

## Files
- `chestCancerDetection.ipynb`: Jupyter notebook containing the code for model creation, training, evaluation, and testing.
- `dataset.txt`: Text file containing the link to the dataset used in the project.
- `model/best_model.h5`, `model/best_model_resnet.h5`, `model/best_model_inceptionv3.h5`: Saved models for EfficientNetB3, ResNet50, and InceptionV3, respectively.
- `model/final_ensemble_model.h5`: Saved ensemble model.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/praiseprince/chestCancerDetection.git

