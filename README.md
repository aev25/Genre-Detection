# Genre Detection

This project's goal was to use audio characteristics gathered from songs to identify different musical genres. I tested how effectively audio attributes can predict a song's genre using data management, machine learning, and deep learning techniques. In order to evaluate spectrogram images, this required cleaning datasets, building machine learning models, and putting the use of convolutional neural networks (CNN).

## Dataset

The dataset can be accessed from Kaggle:
[GTZAN Dataset - Music Genre Classification](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/data)

## Setup Instructions
### 1. Creating the Virtual Environment

To isolate project dependencies, create a virtual environment:

```
python -m venv venv
```

### 2. Activating the Virtual Environment

Activate the virtual environment with the following command:

For Linux/Mac

```
source ./venv/bin/activate
```

For Windows

```
.\venv\Scripts\activate
```

### 3. Installing Required Libraries

Install all necessary libraries by running:

```
pip install pandas numpy librosa matplotlib seaborn scikit-learn tensorflow sqlalchemy
```

### 4. Running the Prediction Notebook

Open and execute the `genre_detection_CS210.ipynb` Jupyter Notebook cell by cell to train and evaluate the model.
