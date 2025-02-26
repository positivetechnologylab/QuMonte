# Quantum Computing for Financial Risk Analysis: Pricing Fixed-Income Assets with QuMonte

***This work was selected for presentation in the [2025 ACM CGO Student Research Competition (SRC)](https://2025.cgo.org/track/cgo-2025-student-research-competition#event-overview).*** Access the abstract [**`here`**](QuMonte_SRC_Abstract.pdf) and the poster [**`here`**](QuMonte_SRC_Poster.png).

## Usage
1. In your terminal, run `git clone https://github.com/positivetechnologylab/QuMonte.git` to clone the repository.
2. Run `cd QuMonte`.
3. Create a virtual environment if necessary, and run `pip install -r requirements.txt` to install the requirements.
4. Run the notebook `Pricing_Fixed_Income_Assets.ipynb`, which contains various functions that are used to simulate fixed-income asset pricing using an optimized quantum circuit.

## Requirements
The requirements and specific versions are provided in `requirements.txt`. Furthermore, this code assumes you have a CPU and GPU available; otherwise, the optimization score calculation will not work.

## Repository Structure
- [**`Pricing_Fixed_Income_Assets.ipynb`**](Pricing_Fixed_Income_Assets.ipynb): This notebook contains code for implementing quantum-enhanced Monte Carlo simulations for pricing fixed-income assets. It features an optimized 5-qubit quantum circuit using Rx and Rz gates and the BOBYQA optimizer to minimize gate depth, reduce noise, and improve accuracy.
- [**`README.md`**](README.md): Repository readme with setup and execution instructions.
- [**`requirements.txt`**](requirements.txt): Requirements to be installed before running the Python scripts.

## Copyright
Copyright © 2025 Positive Technology Lab. All rights reserved. For permissions, contact ptl@rice.edu.
