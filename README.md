# Student Score Prediction Using Linear Regression

## Project Overview
This project predicts a student's score based on the number of hours studied using **Linear Regression**.  
It demonstrates:
- Reading and visualizing data using **Pandas** and **Matplotlib**.
- Implementing **Linear Regression** from scratch using **NumPy**.
- Evaluating the model with **Mean Squared Error (MSE)**.
- Visualizing the learning process and prediction results.


## Dataset
- The dataset is located in the `data` folder: `student_scores.csv`.
- Feature: `Hours` – number of study hours.
- Target: `Scores` – actual student scores.


## Project Structure
─.ipynb_checkpoints

─ data/                     # Contains the dataset CSV file

─ results/                  # Contains generated plots
   ├─ plot1_DataDistribution.png
   ├─ plot2_LossvaluesVsIterations.png
   └─ plot3_FitingLine.png

─ summary/                  # Contains handwritten summary images
   ├─ 1.png
   └─ 2.png

─ linear_regression_model.ipynb  # Jupyter Notebook with the code

─ README.md


## Plots
1. **Data Distribution** – Data visualisation: hours vs scores (`plot1_DataDistribution.png`).
2. **Loss Values vs Iterations** – shows how the model converges (`plot2_LossvaluesVsIterations.png`).
3. **Fitting Line** – shows the prediction modal (`plot3_FitingLine.png`).


## Model Equation
After training, the prediction model is: 
H(x) = theta_0 + theta_1 * x
H(x) = 1.63 + 9.89 * x


##Example prediction:  
Hours = 9 → Predicted Score =90.72996909265946
 

##Model Performance:  
- Mean Squared Error (MSE) = 29.03079707017498


## Requirements
- Python 3.13.5
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`

Author
Nada Ikram Boutiche
