# Car Price Prediction Model

This project implements a Car Price Prediction model using the XGBoost algorithm, achieving high accuracy. Additionally, a GUI (Graphical User Interface) has been developed to allow users to input car attributes and predict the car's purchase amount.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [GUI](#gui)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
The goal of this project is to predict the selling price of a car based on various features such as present price, kilometers driven, fuel type, seller type, transmission type, owner type, and car age. The model has been built using the XGBoost algorithm, which is known for its efficiency and accuracy.

## Features
- Accurate car price prediction using XGBoost.
- User-friendly GUI for easy input and prediction.
- Supports multiple car attributes for detailed prediction.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the model training script (if not already trained):
   ```bash
   python train_model.py
   ```
2. Launch the GUI application:
   ```bash
   python gui_app.py
   ```
3. Enter the following car attributes in the GUI to predict the purchase amount:
   - Present Price (`p1`)
   - Kilometers Driven (`p2`)
   - Fuel Type (`p3`)
   - Seller Type (`p4`)
   - Transmission (`p5`)
   - Owner (`p6`)
   - Age (`p7`)

4. Click the "Predict" button to get the predicted purchase amount.

## Dataset
The dataset used for training the model contains various features of cars, including their present price, kilometers driven, fuel type, seller type, transmission type, owner type, and age. Ensure the dataset is placed in the appropriate directory before training the model.

## Model
The model is built using the XGBoost algorithm, which provides high accuracy and efficiency. The model is trained on the car dataset and achieves the best accuracy for predicting car prices.

## GUI
The GUI is built using Python's Tkinter library. It provides an intuitive interface for users to input car attributes and get the predicted purchase amount.

## Results
The model achieves high accuracy on the test dataset, making it a reliable tool for car price prediction.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The XGBoost library for providing an efficient and accurate machine learning model.
- The Tkinter library for the GUI implementation.
