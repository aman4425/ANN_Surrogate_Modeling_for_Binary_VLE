# Artificial Neural Network in Chemical Engineering

This project demonstrates the use of Artificial Neural Networks (ANNs) to model and analyze 
binary azeotropic VLE (Vapor–Liquid Equilibrium) data in the context of Chemical Engineering. 
The implementation is carried out in a Jupyter Notebook, combining data preprocessing, ANN design, 
training, and result visualization.

## Project Objectives
- Apply ANN techniques to chemical engineering problems.
- Model azeotropic VLE behavior using experimental/simulated datasets.
- Train, validate, and test ANN models for prediction accuracy.
- Compare ANN results with conventional thermodynamic models.

## Repository Structure
- Artificial_Neural_Network_in_Chemical_Engineering.ipynb  - Main notebook
- README.md                                                - Project documentation
- data/                                                    - Dataset folder (if applicable)
- results/                                                 - Saved figures, plots, or model files

## Methodology
### 1. Dataset
- Binary azeotropic VLE dataset used as input.
- Features: mole fraction, temperature, pressure, etc.
- Target: equilibrium composition or property of interest.

### 2. Model Design
- ANN with input, hidden, and output layers.
- Activation functions: ReLU / sigmoid (depending on the layer).
- Optimizer: Adam / SGD.
- Loss function: Mean Squared Error (MSE).

### 3. Training & Validation
- Data split into training and test sets.
- Model trained with backpropagation.
- Evaluation metrics: MAE, RMSE, R² score.

### 4. Results
- Training and validation loss curves.
- Predicted vs experimental values.
- Error analysis and discussion.

##  How to Run
### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries:
  pip install numpy pandas matplotlib scikit-learn tensorflow keras

### Steps
1. Clone this repository or download the notebook
2. Launch Jupyter Notebook:
   jupyter notebook or any ipynb supported IDE.
3. Open Artificial_Neural_Network_in_Chemical_Engineering.ipynb and run all cells.

##  Results & Observations
- ANN successfully modeled the azeotropic VLE system.
- Predicted results closely matched experimental values.
- ANN approach provides flexibility where conventional models face limitations.

##  References
- DWSIM FOSSEE Project: ANN Modeling of Binary Azeotropic VLE using Python.
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning.
- Chemical Engineering Thermodynamics textbooks.

##  Author
Developed by Aman Prakash as part of evaluation project in Artificial Neural Networks 
in Chemical Engineering Applications.
