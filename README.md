# 120 Dog Breed Classification

## About the Project
This project aims to develop a dog breed classification model using a dataset of 120 dog breeds obtained from Kaggle. Built using deep learning techniques with TensorFlow and Keras libraries, the project's objective is to accurately classify the breed of dogs from given images.

## Data Preprocessing
The project includes the following steps for data preparation and model training:
- Loading images and normalizing pixel values.
- Converting categorical labels (dog breeds) to numerical format using Label Encoding.
- Splitting the dataset into training, validation, and testing sets.

## Model Building and Training
The model comprises various layers (Conv2D, MaxPooling2D, Flatten, Dense, Dropout) and uses the 'softmax' activation function. It has been improved through hyperparameter optimization, and the training results have been thoroughly analyzed.

## Installation
To run this project on your local machine, follow these steps:

1. Clone or download this repository:
git clone https://github.com/Mert-Bulut/deep-learning.git

2. Install the required libraries:
pip install -r requirements.txt

## Usage
This project has been developed on Google Colab and includes a Jupyter Notebook file with a `.ipynb` extension. To run the project:
1. Open the `.ipynb` file in Google Colab.
2. From the top menu, select 'Runtime' -> 'Run all' to execute all cells.

## File Structure
- `dog_breed_classification.ipynb`: The main Jupyter Notebook file of the project.
- `requirements.txt`: A list of Python libraries required for the project.
- `data/`: Folder containing the dataset. (Note: The dataset is not shared on GitHub.)

## Technologies
- Python
- TensorFlow
- Keras
- Pandas, NumPy, Matplotlib, Seaborn

## Contributors
This project was developed individually by Mert Bulut.

## License
This project is licensed under the MIT License. For more information, see the `LICENSE` file.
