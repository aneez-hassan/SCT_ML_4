# SCT_ML_4
# Hand Gesture Recognition using Machine Learning

## Overview
This project implements a hand gesture recognition model to classify different hand gestures such as 'fist' and 'open hand'. The system uses computer vision techniques and machine learning algorithms to enable intuitive human-computer interaction and gesture-based control.

## Dataset
- Synthetic dataset with images of hand gestures.
- Dataset was augmented using OpenCV to increase diversity and size.
- Augmentation techniques include flipping, rotation, and scaling.

## Methodology
1. Extracted features from images (e.g., using landmark detection or raw pixel data).
2. Trained a Support Vector Machine (SVM) classifier to differentiate between gestures.
3. Evaluated model accuracy and performance.

## Results
- Achieved high accuracy on the augmented dataset.
- Demonstrated the effectiveness of image augmentation in improving model robustness.

## Usage
- Run the provided Jupyter/Colab notebook to train and test the model.
- Dataset is organized in folders per gesture class.
- Augmented dataset available in `/content/dataset_augmented`.

## Dependencies
- Python 3.x
- OpenCV
- scikit-learn
- mediapipe (optional for landmark extraction)
- numpy
- matplotlib

## Future Work
- Collect real-world hand gesture images.
- Integrate real-time gesture recognition using webcam input.
- Experiment with deep learning models like CNNs for improved accuracy.

---

**Author:** Aneez Hassan  
**Internship Track:** Machine Learning at SkillCraft Technology  
