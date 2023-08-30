# Fake News Detection Project


This project aims to detect fake news using machine learning techniques. It includes data preprocessing, feature extraction, model training, and deployment.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The project focuses on developing a machine learning model to classify news articles as either real or fake. It includes various steps such as data preprocessing, text feature extraction using TF-IDF, model training (Logistic Regression), evaluation, and deployment.

## Installation

1. Clone this repository:
git clone https://github.com/yyigitturan/fake-news-detection.git
2. Navigate to the project directory:
cd fake-news-detection
3. Install the required dependencies:
 pip install numpy pandas scikit-learn nltk seaborn matplotlib



## Usage

1. Run the preprocessing script to clean and preprocess the data.
2. Run the model training script to train the fake news detection model.

## Data
The dataset link: https://www.kaggle.com/competitions/fake-news
The dataset consists of three CSV files:

- `train.csv`: A full training dataset containing news articles with attributes:
- `id`: Unique ID for a news article.
- `title`: The title of a news article.
- `author`: Author of the news article.
- `text`: The text of the article; could be incomplete.
- `label`: A label that marks the article as potentially unreliable (1) or reliable (0).

- `test.csv`: A testing dataset with the same attributes as `train.csv`, excluding the label.


## Model

The machine learning model used for fake news detection is a Logistic Regression classifier trained on TF-IDF features. The model is evaluated on a test set and its performance metrics are assessed.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for suggestions, bug reports, or improvements.

## License

This project is licensed under the [MIT License](LICENSE).
