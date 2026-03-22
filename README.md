# Deepfake Image Detection

This project focuses on deepfake image detection using deep learning models in Google Colab.

## Project Overview
- The dataset was loaded directly from Kaggle in Colab.
- Since the dataset was very large, only a subset/portion of the dataset was used.
- Multiple CNN-based models were applied and compared.

## Models Used
- Custom CNN
- MobileNet
- ResNet50
- VGG19
- EfficientNet

## Model Comparison

| Model        | Accuracy |
|--------------|----------|
| CNN          | 0.9105   |
| MobileNet    | 0.5000   |
| ResNet50     | 0.7311   |
| VGG19        | 0.5000   |
| EfficientNet | 0.5000   |

## Best Model
The Custom CNN model achieved the best performance with an accuracy of 0.9105.

## Dataset
The dataset is not uploaded to this repository because it is large in size.
It was loaded directly from Kaggle in Google Colab, and only a subset was used for training and evaluation.
Dataset Path:
import kagglehub
# Download latest version
path = kagglehub.dataset_download("birdy654/cifake-real-and-ai-generated-synthetic-images")
print("Path to dataset files:", path)

## Workflow
1. Load dataset from Kaggle
2. Select a subset of images
3. Preprocess images
4. Train multiple models
5. Compare model performance
6. Evaluate results

## Repository Files
- `deepfake_image.ipynb` → complete Colab notebook
- `requirements.txt` → required libraries
- `.gitignore` → ignored files

## Future Improvements
- Improve accuracy of transfer learning models
- Train on a larger subset of the dataset
- Try Vision Transformers and CLIP-based approaches
- built a GUI Interface
