# Epidemic Spread Simulation (Agent-Based Model)

## Overview

This project implements an **agent-based epidemic simulation** using NetLogo. It models how an infectious disease spreads through a population based on movement, proximity, and epidemiological parameters.

The model follows an extended **SEIR framework**:

* Susceptible
* Exposed (Carriers)
* Infectious
* Recovered

---

## Model Features

* Individual-based simulation (each agent represents a person)
* Adjustable epidemiological parameters
* Real-time visualization of disease spread
* Dynamic epidemic curve and daily case tracking
* Vaccination effects included

---

## Parameters

| Parameter           | Description                               |
| ------------------- | ----------------------------------------- |
| population-size     | Total number of individuals               |
| mobility            | Movement speed of agents                  |
| transmission-radius | Distance within which infection can occur |
| transmission-rate   | Probability of infection per contact      |
| mortality-rate      | Probability of death after infection      |
| incubation-period   | Time before exposed becomes infectious    |
| recovery-period     | Time to recover                           |
| vaccination-rate    | Number of individuals vaccinated          |

---

## Outputs

### 1. Simulation View

* Agents move randomly
* Color-coded states:

  * Green → Susceptible
  * Orange → Exposed
  * Red → Infectious
  * Blue → Recovered

### 2. Epidemic Curve

Tracks population over time:

* Susceptible
* Exposed
* Infectious
* Recovered

### 3. Daily Cases Graph

Shows fluctuation in infection rates

### 4. Key Metrics

* Total deaths
* Peak daily cases
* Current population distribution

---

## Model Figure

![Simulation Interface](docs/model_figure.png)

---

## How to Run

1. Install NetLogo (https://ccl.northwestern.edu/netlogo/)
2. Open:

   ```
   model/Epidemic_model.nlogo
   ```
3. Click:

   * `Setup`
   * `Go`
4. Adjust sliders to experiment with different scenarios

---

## Research Applications

This model can be used for:

* Studying epidemic dynamics
* Testing intervention strategies
* Exploring vaccination impact
* Sensitivity analysis of parameters

---

## Limitations

* Assumes homogeneous population behavior
* No spatial clustering or real geography
* Simplified transmission model

---

## Future Improvements

* Add social network structure
* Introduce age groups
* Include lockdown policies
* Real-world data calibration

---

## Prerequisites
To run the files in this repository, you will need:
* **NetLogo 7.0.3** (or later) to run the `.nlogox` simulation.
* **Python 3.x** and **Jupyter Notebook** to run the ML model.
* Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
