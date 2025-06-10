# molecular-property-prediction
This project develops a deep learning model to predict aqueous solubility (logS) of organic molecules using their SMILES (Simplified Molecular Input Line Entry System) strings.

The model uses RDKit to compute molecular descriptors and a Keras-based neural network for regression. It demonstrates the integration of cheminformatics and machine learning for property prediction.

## Features
Convert SMILES strings to molecular descriptors using RDKit

Normalize and preprocess chemical data for training

Build and train a deep neural network using Keras

Evaluate model performance with RMSE and R² metrics

Visualize training loss and feature importance

## Getting Started
## Prerequisites
Make sure you have Python 3.x installed along with the following libraries:

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow rdkit

## How to Run
Clone this repository.

Open the Jupyter notebook file molecular_property_predictor.ipynb.

Run all cells step-by-step to:

Load and process the dataset

Generate molecular descriptors

Train the neural network

Evaluate and visualize results

## Dataset
The dataset (esol.csv) contains SMILES strings and aqueous solubility values (logS) for around 1128 organic compounds. It is a benchmark dataset widely used in cheminformatics for evaluating regression models.

## Project Structure
molecular-property-predictor/
├── molecular_property_predictor.ipynb # Main Jupyter notebook with code
├── esol.csv # Dataset file with SMILES and logS values
├── README.txt # Project documentation (this file)

## Author
Aarohi Jain
B.Tech Student - Robotics & AI
Manav Rachna University
Email: aarohi.jain.2007@gmail.com

## License
This project is open source and available under the MIT License.

Feel free to connect or ask questions!
