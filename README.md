# CV1 Lab 1

This repository contains the Jupyter Notebook for **Lab 1** of the **Computer Vision 1** course, part of the **Master's in Artificial Intelligence** program at the **University of Amsterdam**. The lab exercises are designed to deepen your understanding of key computer vision concepts and provide hands-on experience with popular Python libraries such as OpenCV, NumPy, and Matplotlib.

## Table of Contents

- [Overview](#overview)
- [Environment Setup](#environment-setup)
- [File Structure](#file-structure)

## Overview

Digital cameras are everywhere, embedded in consumer cameras, webcams, mobile phones, and professional equipment. These devices generate vast amounts of data, crucial for communication, observation, and interaction. This course focuses on the computational techniques used to enable computers to understand the visual world, with a particular emphasis on scene understanding and object recognition.

The course covers a wide range of topics, including:
- Image formation and filtering
- Feature extraction (color and shape invariants, interest point detectors, descriptors like SIFT and HoG)
- Visual information representation (vector space, statistical models, Bag-of-Words)
- Learning and classification techniques, including deep learning (DL)
- Object detection and classification, object tracking

## Environment Setup

To avoid errors and ensure that your code runs correctly for the TAs, it is **mandatory** to use the specified Python environment. You can set up the environment using the `cv1_environment.yaml` file included in this repository.

To create the environment, run:

```bash
conda env create -f cv1_environment.yaml
conda activate cv1
```

This environment includes the following key libraries and their versions:

- **NumPy**: 1.26.4
- **OpenCV (Contrib)**: 4.10.0
- **Matplotlib**: 3.9.2

Ensure that you're using these versions to avoid compatibility issues.

## File Structure

```markdown
cv1-lab-1/
│
├── images/
│   └── (images used in the exercises)
├── intrinsic_images/
│   └── (images used for intrinsic image decomposition)
├── photometrics_images/
│   └── (images used for photometric stereo exercises)
├── computer-vision-a-modern-approach-chapter-5.pdf
├── cv1_environment.yaml
├── cv1-lab-1.ipynb
├── LICENSE
└── README.md
```