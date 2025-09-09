# UPRM Hackathon 2025: Multilabel CNN Image Classification

## Project Description
This repository contains the source code for a Convolutional Neural Network (CNN) based multilabel image classification project developed for the 2025 UPRM Hackathon, hosted in collaboration with Lockheed Martin. Our solution aims to demonstrate the power of deep learning in handling complex image datasets where each image may belong to multiple categories simultaneously.

## UPRM Hackathon & Lockheed Martin
The University of Puerto Rico at Mayagüez (UPRM) Hackathon is an annual event that brings together student teams to solve real-world problems using technology and innovation. Sponsored by Lockheed Martin, the hackathon provides an excellent opportunity for students to tackle challenging engineering and computer science problems, gain hands-on experience, and network with industry professionals.

## CNN Multilabel Image Classification Purpose
Multilabel image classification enables a model to assign multiple tags or classes to a single image, which is essential for real-world scenarios such as object detection, medical imaging, and automated tagging systems. Our project leverages a CNN architecture to learn and predict multiple labels for each image, focusing on accuracy, efficiency, and scalability.

## Dataset
We used the [NASA Geographical Objects Multilabel Dataset](https://www.kaggle.com/datasets/olebro/nasa-geographical-objects-multilabel-dataset), which contains diverse satellite imagery labeled with multiple geographical object categories. The dataset can be automatically downloaded using `kagglehub` as follows:

```python
import kagglehub
path = kagglehub.dataset_download("olebro/nasa-geographical-objects-multilabel-dataset")
```

## Technologies Used
- Python
- PyTorch (Deep Learning Framework)
- Torchvision (Pretrained Models & Image Transformations)
- OpenCV (Image Processing, via opencv-python-headless)
- NumPy (Numerical Computation)
- Pandas (Data Handling & Manipulation)
- Matplotlib & Seaborn (Data Visualization)
- scikit-learn (Metrics, Data Splitting, Resampling)
- tqdm (Progress Bars)
- kagglehub (Dataset Download and Integration)

## Credits / Contributors
This project was developed by a multidisciplinary team for the UPRM Hackathon 2025:
- J3SSY-ANDU
- Chosen-Juan1
- Special thanks to Lockheed Martin and UPRM organizers

---

Feel free to reach out if you have any questions or would like to contribute!
