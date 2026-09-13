# Experiment 3: Python Data Analysis (Pandas)
**Course:** ECE 2112: Advanced Computer Programming and Algorithms

---

## Overview
This repository/Jupyter Notebook contains the solutions for **Experiment 3**, focusing on data manipulation, indexing, slicing, and subsetting using the **Pandas** library in Python[cite: 1].

---

## Dataset Description
The dataset used (`cars.csv`) contains automotive performance and specification metrics with the following columns[cite: 1]:
* `Model`: Vehicle model name[cite: 1]
* `mpg`: Miles/(US) gallon[cite: 1]
* `cyl`: Number of cylinders[cite: 1]
* `disp`: Displacement (cu.in.)[cite: 1]
* `hp`: Gross horsepower[cite: 1]
* `drat`: Rear axle ratio[cite: 1]
* `wt`: Weight (1000 lbs)[cite: 1]
* `qsec`: 1/4 mile time[cite: 1]
* `vs`: V/S (0 = V-shape, 1 = Straight)[cite: 1]
* `am`: Transmission (0 = automatic, 1 = manual)[cite: 1]
* `gear`: Number of forward gears[cite: 1]
* `carb`: Number of carburetors[cite: 1]

---

## Programming Problems & Solutions

### I. Positional and Label-Based Slicing
* **a. Dataset Shape & Columns:** Displays the dimensions and column labels of the main DataFrame[cite: 1].
* **b. Positional Slicing (`cars_6_to_10`):** Extracts rows 6 through 10 (1-indexed) using `iloc`[cite: 1].
* **c. Column Filtering:** Narrows down `cars_6_to_10` to specific columns (`Model`, `mpg`, `cyl`, `hp`, and `gear`)[cite: 1].

### II. Model Lookup
* **a. Toyota Corolla:** Uses Boolean indexing to retrieve all specifications for the Toyota Corolla[cite: 1].
* **b. Pontiac Firebird:** Extracts specific columns (`Model`, `mpg`, `hp`, `wt`) for the Pontiac Firebird without hardcoded row indices[cite: 1].

### III. Multi-Model Subsetting (`selected_cars`)
* Filters records for **Datsun 710**, **Lotus Europa**, and **Ferrari Dino** using their model names[cite: 1].
* Retains columns `Model`, `mpg`, `cyl`, `hp`, and `gear`[cite: 1].
* Verifies that the resulting DataFrame has dimensions of **(3, 5)**[cite: 1].

---

## Submission Requirements
* Submit one Jupyter Notebook file (`.ipynb`) with clearly labeled solutions and executed outputs[cite: 1].
* Ensure the notebook runs cleanly from beginning to end without errors[cite: 1].
