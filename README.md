# Skin Cancer Detection using CNN with Hair Removal Algorithm

## Project Overview
This project focuses on classifying skin lesions using deep learning.
The HAM10000 dataset was used, with approximately 10% of the dataset selected
for the experiment.

## Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- CNN
- MobileNetV2
- OpenCV
- NumPy
- Pandas
- Matplotlib

## Dataset
HAM10000 dataset containing 10,015 dermoscopic images and 7 lesion classes.

Classes:
- akiec
- bcc
- bkl
- df
- mel
- nv
- vasc

## Methodology
1. Dataset collection
2. Dataset preprocessing
3. Hair detection
4. Hair removal using Black-hat morphology and inpainting
5. CNN model training
6. MobileNetV2 transfer learning
7. Model evaluation
8. Sample prediction

## Results

| Model | Test Accuracy |
|---|---:|
| Baseline CNN | 67.55% |
| Improved Model | 13.91% |
| MobileNetV2 | 74.83% |

## Best Model
MobileNetV2 achieved the best test accuracy of **74.83%** in this experiment.

## Note
This project is for educational/research purposes and is not intended
for medical diagnosis.
