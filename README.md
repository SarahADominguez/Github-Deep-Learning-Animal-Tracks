
# Animal Footprint Classification Using Deep Learning 

### ResNet | Transformers | Computer Vision | PyTorch | Python

## Project Overview

This project explores the use of deep learning and computer vision to identify animal species from images of their footprints.

Animal tracks can vary significantly in shape, texture, size, and environmental conditions, making automated classification an interesting computer vision challenge.

To investigate different approaches, this project compares multiple neural network architectures, including ResNet-based convolutional models and a Transformer-based approach.

The project also includes a Python-based user interface for interacting with the animal footprint classification model.

## Project Objectives

- Develop deep learning models capable of classifying animal footprints from images.
- Explore the effectiveness of convolutional neural networks and Transformer architectures.
- Investigate transfer learning and layer-freezing techniques using ResNet.
- Compare different modeling approaches for image classification.
- Build a user-facing application that demonstrates the classification process.

## Deep Learning Models

### 1. ResNet — Standard

A ResNet-based image classification approach used to explore convolutional neural networks for recognizing animal footprint patterns.

**Notebook:** `OpenAnimalTracks-ResNet-Standard.ipynb`

### 2. ResNet — Layer Freezing

An additional ResNet experiment exploring how freezing layers during training can affect the model adaptation process.

**Notebook:** `OpenAnimalTracks-ResNet-WithFreezing.ipynb`

### 3. Transformer

A Transformer-based experiment exploring an alternative architecture for learning visual patterns from animal footprint images.

**Notebook:** `OpenAnimalTracks-Transformer.ipynb`

## Technologies Used

- **Python** — Model development and application logic
- **PyTorch** — Deep learning development
- **ResNet** — Convolutional neural network architecture
- **Transformers** — Alternative deep learning architecture
- **Jupyter Notebook** — Model experimentation and analysis
- **Computer Vision** — Image-based animal footprint classification

## Dataset

The project uses the OpenAnimalTracks dataset to investigate animal footprint classification.

The dataset includes animal track imagery used for developing and evaluating the models.

Due to its size, the full dataset is not included directly in this GitHub repository.

## Project Structure

- `OpenAnimalTracks-ResNet-Standard.ipynb` — Standard ResNet experiment
- `OpenAnimalTracks-ResNet-WithFreezing.ipynb` — ResNet layer-freezing experiment
- `OpenAnimalTracks-Transformer.ipynb` — Transformer experiment
- `animal_tracks_model20.pth` — Saved model weights
- `User_Interface.py` — Python application interface

## Application Demonstration

A video presentation is available demonstrating the project and its animal footprint classification application.

**[Watch the Project Presentation](sha256:547d7590ed92eeaf0c00411abaf75ae0c6ab9dd384f310aa4bff9281ea9378cc)**

## Future Improvements

Potential areas for further exploration include:

- Comparing model performance across individual animal classes.
- Expanding the dataset with more diverse environmental conditions.
- Investigating data augmentation to improve generalization.
- Exploring additional architectures and transfer learning strategies.
- Improving the accessibility and deployment of the classification interface.

## About This Project

This project demonstrates practical applications of deep learning, computer vision, neural network experimentation, and model development through the challenge of animal footprint recognition.
