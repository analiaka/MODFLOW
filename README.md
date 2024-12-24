# Working with MODFLOW
Setting up a simple steady-state well model using MODFLOW, the widely utilized groundwater modeling software developed by the USGS
# MODFLOW 

This repository contains a Jupyter Notebook tutorials for the following:
1. The essential steps to create and configure a MODFLOW model that simulates groundwater flow under steady-state conditions and visualizing MODFLOW groundwater simulation results.
2. The step-by-step process for loading and utilizing an existing MODFLOW model, specifically the COHYST (Cooperative Hydrology Study) groundwater model. 

## Notebooks Overview

| Notebook | Description |
|----------|-------------|
| [CPNRD MODFLOW.ipynb](notebook1.ipynb) | This notebook demonstrates how to load and run the **COHYST** MODFLOW model. |
The notebook includes:
- Configuring the model folder
- Loading the model
- Running the model
- Handling errors


| [Steady-State Pumping Well using MODFLOW.ipynb](notebook2.ipynb) | This notebook focuses on visualizing hydraulic head outputs using **Flopy**. |
The notebook includes:
- Creating the model
- DIS Package
- BAS Package
- LPF Package
- WEL PAckage
- OC Package
- PCG Package
- Writing files and running the model
- Post processing and visualization
- Hydraulic head contours
- Flow vectors (discharge arrows)
- Model grid visualization  

## Requirements
- Python 3.x
- FloPy
- Matplotlib
- Numpy
- MODFLOW or MODFLOW-2005 executables
- COHYST Groundwater model

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
