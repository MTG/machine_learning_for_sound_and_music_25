# Machine Learning for Sound and Music

## Overview

This repository contains materials for the "Machine Learning for Sound and Music" course. The course introduces key concepts of machine learning applied to audio and music processing. The materials include lecture notebooks, practical exercises, and examples to help students learn and implement machine learning techniques effectively.

## Repository Structure

- `notebooks/`: Contains Jupyter notebooks for each lecture.
- `docker/`: Includes Docker files to build the image and run the Jupyter server.

## Getting Started

### Prerequisites

- Docker and Docker Compose installed on your machine.
- Basic familiarity with Python and Jupyter Notebooks.
- Recommended: A laptop with a GPU for deep learning tasks.

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd machine_learning_for_sound_and_music
   ```

2. Build the Docker image:

   ```bash
   docker-compose build
   ```

3. Start the Jupyter server:

   ```bash
   docker-compose up
   ```

4. Access the Jupyter server:
   Open your browser and navigate to `http://localhost:8888`.

## Course Content

### Lecture Index

- **Lecture 5: Supervised Learning with CNNs**
  - 05_01_Review_of_CNNs: Review of CNNs, examples of music multi-label tasks, and training a small autotagging model.
  - 05_02_Multiclass_Classification: Understanding softmax vs sigmoid activation and cross-entropy vs binary cross-entropy loss.
  - 05_03_Evaluation_Metrics: Evaluation metrics such as accuracy, ROC-AUC, and PR-AUC.

- **Lecture 6: Self-Supervised Learning I: Autoencoders**
- **Lecture 7: Self-Supervised Representation Learning II: Metric Learning**
- **Lecture 8: Transformers and the Attention Mechanism**
- **Lecture 9: Transfer Learning**
- **Lecture 10: Multi-modal Learning: Text-Audio Models**

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or suggestions.

## References

- [mirdata](https://mirdata.readthedocs.io/en/stable/): Dataset loader used in the course.
- PyTorch: Preferred library for deep learning tasks.
- Essentia: Library for audio processing.

## License

This repository is licensed under the MIT License. See the LICENSE file for details.
