# Road Mark Detection with YOLOv8

## Overview

Welcome to the Road Mark Detection project using YOLOv8! This repository contains the implementation of an object detection model trained to identify and classify road markings. Whether you're interested in enhancing autonomous vehicle capabilities or improving traffic management systems, this project serves as a valuable resource.

## Table of Contents

- [Project Highlights](#project-highlights)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Training Your Own Model](#training-your-own-model)
- [Performance Metrics](#performance-metrics)
- [Dataset](#dataset)
- [Results](#results)

## Project Highlights

- Implemented road mark detection using the YOLOv8 object detection algorithm.
- Detailed insights into the training process, including dataset preparation and parameter fine-tuning.
- Performance metrics such as accuracy, precision, and recall are optimized for reliable road mark detection.
- Real-world applications and implications discussed for a broader understanding.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- [PyTorch](https://pytorch.org/) (Follow the installation instructions on their website)
- Other dependencies: `numpy`, `opencv-python`, etc. (Install using `pip install -r requirements.txt`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/road-mark-detection.git
   cd road-mark-detection

1. Install dependencies:

       pip install -r requirements.txt

## Usage

To use the pre-trained model for road mark detection, run:

## Training Your Own Model

If you want to train your own YOLOv8 model for road mark detection, follow these steps:

### 1. Dataset Preparation

Prepare a dataset containing annotated images of road markings. The annotations should include bounding boxes around the road marks. Organize the dataset into a directory structure like this:

    dataset/
    |-- images/
    | |-- image1.jpg
    | |-- image2.jpg
    | |-- ...
    |-- labels/
    | |-- image1.txt
    | |-- image2.txt
    | |-- ...
    | |-- data.yaml

![image](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/6575a791-80f1-4f7a-abf8-f1e221288764)


## Performance Metrics

Explore the model's performance metrics, including accuracy, precision, and recall, in Performance Metrics.

![Untitled](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/2fa71ef2-e89a-4b1d-a04b-a51ee95910ce)
![P_curve](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/b9a336b8-ecb5-4ea0-aa4c-68d6d686414e)
![R_curve](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/3c63087c-3ead-4ca1-8d84-66ba572ea2f5)
![PR_curve](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/703e2569-b1c6-41fd-9e1b-a51730b27dbf)


## Dataset

Information about the dataset used for training and evaluation is available on GitHub. 
dataset link:- https://www.kaggle.com/datasets/pkdarabi/road-mark-detection

## Results

View the results and insights gained from the project in Results.

![Untitled-1](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/542a353d-bffe-46b9-b695-427e41968a90) ![Untitled](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/932a31de-ec54-44a8-a70b-d46cec53b615) ![Untitled-1](https://github.com/rkgupta7463/Road-Mark-Detection-Project/assets/96177171/159434dd-1357-4be9-9822-64c90a4ca92f)



