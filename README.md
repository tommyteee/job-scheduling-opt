Job Scheduling Optimization Using Pyomo and Gurobi

<img width="170" alt="image" src="https://github.com/user-attachments/assets/8c7827e6-d837-4ce5-acc6-268531af6208" />



Overview

This project formulates and solves a job scheduling optimization problem to maximize total profit while ensuring that the total job duration does not exceed the available working hours over 3 days. The model selects the most profitable combination of jobs based on their duration and profit values. The optimization is implemented using Pyomo and solved with the Gurobi solver.

Key Features

Optimizes job scheduling to maximize total profit

Ensures job duration constraints within daily working hours

Uses binary decision variables to determine job selection

Implements Gurobi, a high-performance solver for integer programming

Installation

1. Install Required Packages

Ensure you have the following dependencies installed:

pip install pyomo

2. Install Gurobi Solver

Since this project uses Gurobi, you need to install and license it:

Download Gurobi from Gurobi Official Website

Ensure Gurobi is installed and set the correct path in the script if necessary

How to Run the Project

Ensure that all dependencies are installed.

Run the Python script:

python job_scheduling_optimization.py

View the results, which include:

Optimal job selection for each day

Total maximized profit
