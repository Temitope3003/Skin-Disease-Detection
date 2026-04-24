# Skin Disease Detection

A CNN-based deep learning model for classifying skin diseases from medical image data, targeting accessible diagnostics in low-resource settings.

## Problem
Many skin conditions go undiagnosed due to limited access to dermatologists, particularly in underserved communities. This model provides an automated first-pass classification tool from skin images.

## Diseases Detected
- Actinic Keratosis, Basal Cell Carcinoma and other Malignant Lesions
- Atopic Dermatitis
- Bacterial Skin Infection
- Drug Eruptions
- Eczema
- Herpes Simplex
- Acne
- Keratosis Pilaris
- Rosacea

## Dataset
- Source: Kaggle Skin Disease Dataset
- Total images: 8,419
- Image size: 160 x 160 x 3 (RGB)
- Split: Training and validation sets

## Approach
- Loaded and preprocessed 8,419 images across 9 disease classes
- Applied image normalisation and augmentation to improve generalisation
- Trained a CNN-based classifier on labelled image data
- Evaluated model performance using accuracy, precision, recall, and F1-score

## Tech Stack
- Python
- TensorFlow, Keras
- CNN
- NumPy, Pandas
- Matplotlib
- Jupyter Notebook
- Kaggle (dataset source)

## How to Run
```bash
git clone https://github.com/Temitope3003/Skin-Disease-Detection
cd Skin-Disease-Detection
pip install -r requirements.txt
jupyter notebook skin-disease.ipynb
```

## Use Case
Automated skin condition screening tool to support early detection and referral, particularly in settings with limited dermatology access.
