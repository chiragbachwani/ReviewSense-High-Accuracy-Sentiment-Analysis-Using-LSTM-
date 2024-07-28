# ReviewSense: LSTM-Based Sentiment Analysis Model

## Overview

ReviewSense is an advanced sentiment analysis model designed to classify movie reviews into positive or negative categories using Long Short-Term Memory (LSTM) networks. Achieving 85% accuracy on the IMDB dataset, this project showcases the power of LSTM for text sentiment classification.

## Project Features

- **LSTM Model:** Utilizes Long Short-Term Memory (LSTM) networks to analyze and predict sentiment from movie reviews.
- **High Accuracy:** Achieved 85% test accuracy on the IMDB dataset consisting of 50,000 movie reviews.
- **Data Processing:** Implements text tokenization and padding techniques to prepare data for training.
- **Model Optimization:** Employs Adam optimizer and binary cross-entropy loss function for improved performance.
- **Validation and Testing:** Uses a 20% validation split to monitor model performance and prevent overfitting.

## Technologies Used

- **Python:** Programming language used for model development.
- **Keras:** High-level neural networks API for building and training the LSTM model.
- **LSTM:** Recurrent neural network architecture used for processing sequential data.
- **IMDB Dataset:** Dataset containing 50,000 movie reviews used for training and evaluation.

## Installation

To set up this project on your local machine, follow these steps:

1. Ensure that Python 3.x is installed on your system. If not, download and install it from the official Python website.
2. Clone the repository to your local machine. You can use Git to clone the repository, which will create a local copy of the project files.
3. Navigate to the project directory where the repository was cloned.
4. Install the required Python packages. These packages are listed in the `requirements.txt` file, which specifies all the dependencies needed for this project.

## Requirements

You need to create a `requirements.txt` file to list the necessary Python packages. This file should include the following:

- `numpy`
- `pandas`
- `tensorflow`
- `keras`
- `scikit-learn`

## Usage

1. **Prepare Data:**
   - The IMDB dataset should be processed using text tokenization and padding techniques. Ensure the file `imdb_reviews.csv` is available in the `data` folder.
2. **Train the Model:**
   - Use the provided training script to build and train the LSTM model.
3. **Evaluate the Model:**
   - Evaluate the model on the test set to determine its accuracy and loss.

## Project Structure

- `data/`: Contains the IMDB dataset and preprocessed files.
- `models/`: Contains the trained LSTM model.
- `scripts/`: Contains Python scripts for training and evaluating the model.
  - `train_model.py`: Script to train the LSTM model.
  - `evaluate_model.py`: Script to evaluate the trained model.
- `requirements.txt`: Lists the dependencies for the project.

## Results

- **Test Accuracy:** 85%
- **Test Loss:** 0.3

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements

- IMDB dataset for providing the movie reviews.
- Keras and TensorFlow for providing the tools necessary to build and train the LSTM model.
