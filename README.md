# Feature Selection using Tasmanian Devil Optimization (FSTDO)

## Overview

Software quality is improved through early software flaw identification, which is made possible by software fault prediction (SFP). Early software problem identification reduces the amount of money and work needed to fix those vulnerabilities.

This repository presents the implementation of the **FSTDO model**, a novel feature selection (FS) approach built upon **Tasmanian Devil Optimisation (TDO)**. The proposed FSTDO helps to select the optimal feature subset that yields maximum classification accuracy.

## Key Contributions

**Novel Algorithm:** Introduction of FSTDO for optimal feature subset selection.

**Benchmarking:** The algorithm is compared with four well-known FS algorithms:

* Ant Colony Optimisation (ACO)
* Genetic Algorithm (GA)
* Particle Swarm Optimisation (PSO)
* Differential Evolution (DE)

**Classifiers Used:** Performance assessed using **KNN**, **NB**, **DT**, and **QDA**.

**Results:** Experimental outcomes reveal that FSTDO delivers enhanced performance in terms of accuracy and the selection of significantly viable optimal features.

## Publication

This research is published in the **International Journal of Computational Science and Engineering (IJCSE).**

**Title:** Feature selection using Tasmanian devil optimisation algorithm for software fault prediction.

[DOI: 10.1504/IJCSE.2025.143468](https://dx.doi.org/10.1504/IJCSE.2025.143468)

## Getting Started
### Prerequisites

Ensure you have Python installed along with the following libraries:

* numpy
* pandas
* scikit-learn
* matplotlib

### Usage

**1. Clone the repo:**
git clone https://github.com/hrishikeshkumar09/Feature-Selection-Tasmanian-Devil-Optimization-FSTDO.git

**2. Run the Notebook:**
Open the .ipynb file in Jupyter Notebook or VS Code to see the comparative analysis between FSTDO and the other meta-heuristic algorithms.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

