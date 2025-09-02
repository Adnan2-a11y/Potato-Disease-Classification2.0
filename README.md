# 🥔 Potato Disease Classification

## Overview

This project uses deep learning to classify potato diseases from leaf images. Leveraging a convolutional neural network (CNN) and the PlantVillage dataset, the model can identify multiple classes of plant diseases, helping farmers and researchers with early detection and management.

## Features

- Imports and preprocesses the PlantVillage dataset from Kaggle.
- Utilizes TensorFlow and Keras for building and training an advanced CNN.
- Data augmentation and validation split for robust model training.
- Visualizes sample images and predictions.
- Predicts disease class for random images from the dataset.

## Installation

1. Clone this repository or download the files.
2. Install dependencies using pip:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Download the PlantVillage dataset using KaggleHub.
2. Open `Potato_Disease_Classification.ipynb` in Jupyter Notebook or VS Code.
3. Run the cells sequentially to:
    - Import data
    - Preprocess images
    - Train the CNN model
    - Evaluate and visualize predictions

## Project Structure

- `Potato_Disease_Classification.ipynb` — Main notebook containing all code and analysis.
- `requirements.txt` — List of required Python packages.

## Dependencies

- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Pillow
- KaggleHub

## Example Results

- Achieves high accuracy on validation data.
- Correctly classifies random images from the dataset.
- Visualizes predictions with image and class label.

## License

This project is for educational purposes.

---

*Icon by [Icons8](https://icons8.com/icons/set/potato)
