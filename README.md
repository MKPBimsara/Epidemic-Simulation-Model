# Agent-Based Epidemic Spread Simulation & Infection Risk Prediction

This repository contains the code, dataset, and final report for the **Multi-Agent Systems (DSA 560 2.0)** course project. The project is divided into two main phases: an Agent-Based SEIR epidemic simulation and a Machine Learning predictive pipeline.

## Project Contributors
* **Pasindu Bimsara (MSC/DSA/183):** Designed and implemented the epidemic simulation model (NetLogo), programmed transmission dynamics, and engineered the automated dataset extraction.
* **Chathuka Jayasinghe (MSC/DSA/251):** Developed the Machine Learning pipeline (Python/Scikit-learn), conducted data preprocessing, model training (Logistic Regression & Random Forest), and performance evaluation.

## Repository Contents
* `Epidemic_model.nlogox`: The NetLogo simulation file implementing the Agent-Based SEIR (Susceptible, Exposed, Infectious, Recovered) framework. Features tick-by-tick logging of spatial and behavioral data.
* `Infection Risk Prediction ML model.ipynb`: Jupyter Notebook containing the predictive modeling pipeline. Evaluates agent features to predict individual infection risk.
* `infection_risk_dataset.csv`: The behavioral and spatial dataset generated directly from the NetLogo simulation runs.
* `model_figure.png`: Visual representation of the model/simulation.
* `Report.pdf`: The comprehensive final project report detailing the rationale, methodology, system design, and results analysis.

## Prerequisites
To run the files in this repository, you will need:
* **NetLogo 7.0.3** (or later) to run the `.nlogox` simulation.
* **Python 3.x** and **Jupyter Notebook** to run the ML model.
* Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.

## Usage
1. **Simulation:** Open `Epidemic_model.nlogox` in NetLogo. Adjust the global parameters, click "setup", and then "go" to watch the simulation and generate new data.
2. **Machine Learning:** Open `Infection Risk Prediction ML model.ipynb` in Jupyter Notebook. Ensure `infection_risk_dataset.csv` is in the same directory, and run the cells sequentially to train and evaluate the models.