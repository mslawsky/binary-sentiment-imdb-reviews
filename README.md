# IMDb Sentiment Analysis 🎬 

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-blue.svg)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.x-green.svg)](https://keras.io/)
[![Python](https://img.shields.io/badge/Python-3.6+-purple.svg)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.19+-blue.svg)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.1+-green.svg)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![TensorFlow Embedding Projector](https://img.shields.io/badge/Embedding%20Projector-TensorBoard-blueviolet.svg)](https://projector.tensorflow.org/)


## Overview 📖 

This project demonstrates **binary sentiment classifier** for IMDb movie reviews using [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/). The model processes raw text reviews, converts them into numerical sequences, learns word embeddings, and predicts whether a review is **positive** 😊 or **negative** 😞.

---

## Features 🚀 

- Text-to-numeric conversion with embedding layers 🔠 
- Predicts positive or negative sentiment for each review 🏷️ 
- Tracks training and validation accuracy 📈 
- Easily customizable model parameters 🛠️ 
- Exports word embeddings for visualization 🌐 with the [TensorFlow Embedding Projector](https://projector.tensorflow.org/)

---

## Dataset 📦 

- **Source:** [IMDb Movie Reviews](https://ai.stanford.edu/~amaas/data/sentiment/)
- **Description:** 50,000 reviews labeled as positive or negative
- **Format:** Each sample contains review text and a label (`0 = negative`, `1 = positive`)

---

## Getting Started 🛠️ 

### Prerequisites

- Python 3.x
- TensorFlow 2.x
- NumPy
- [Jupyter Notebook](https://jupyter.org/)

### Installation

```bash
git clone 
cd 
pip install -r requirements.txt
```

### Usage

1. Download the IMDb dataset (see [Dataset](#dataset) above).
2. Open and run `C3_W2_Lab_1_imdb.ipynb` in Jupyter Notebook to preprocess data, train, and evaluate the model.
3. Adjust model parameters (embedding size, dense layer size, epochs) as desired.
4. After training, export the embedding weights and metadata for use with the [TensorFlow Embedding Projector](https://projector.tensorflow.org/).

---

## 📂 Code Structure

- `C3_W2_Lab_1_imdb.ipynb` - Main notebook for data loading, preprocessing, model building, training, and evaluation
- `requirements.txt` - List of dependencies

---

## Results 📊 

- Training accuracy: ~99% after 5 epochs
- Validation accuracy: ~80% (can be improved with hyperparameter tuning)
- Loss and accuracy plots available in the notebook

---

## TensorFlow Embedding Projector 🌐 

Visualize the learned word embeddings with the [TensorFlow Embedding Projector](https://projector.tensorflow.org/):

1. After training, export the embedding weights and metadata as described in the notebook.
2. Upload the generated `vectors.tsv` and `metadata.tsv` files to the Embedding Projector.
3. Explore relationships and clusters in the embedding space.

---

## Future Work 🌱 

- Experiment with more complex model architectures (e.g., LSTM, GRU)
- Try multi-class sentiment (e.g., neutral, mixed)

---

## Acknowledgements 🙏 

Special thanks to:
- [Andrew Ng](https://www.andrewng.org/) for creating the Deep Learning AI curriculum and platform
- [Laurence Moroney](https://twitter.com/lmoroney) for excellent instruction and developing the course materials
- The creators of the [IMDb Movie Reviews dataset](https://ai.stanford.edu/~amaas/data/sentiment/) at Stanford AI Lab
- This notebook was created as part of the TensorFlow Certification Program by DeepLearning.AI

---

## Contact 📫

For inquiries about this project:
- [LinkedIn Profile](https://www.linkedin.com/in/melissaslawsky/)
- [Client Results](https://melissaslawsky.com/portfolio/)
- [Tableau Portfolio](https://public.tableau.com/app/profile/melissa.slawsky1925/vizzes)
- [Email](mailto:melissa@melissaslawsky.com)

---

© 2025 Melissa Slawsky. All Rights Reserved.

