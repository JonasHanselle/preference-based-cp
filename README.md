# 🚀 Conformal Prediction without Nonconformity Scores
This repository contains the experimental code for the paper: **"Conformal Prediction without Nonconformity Scores"** by Jonas Hanselle, Alireza Javanmardi, Tobias Oberkofler, Yusuf Sale and Eyke Hüllermeier (UAI 2025).

## Contents

* **conformal/** — core algorithmic implementations
* **experiments/** — scripts to reproduce the experiments
* **models/** — model definitions, checkpoints
* **notebooks/** — exploratory analysis and visualization
* **util/** — utility and helper functions

## Requirements & Setup

1. Install dependencies (e.g. via `pip install -r requirements.txt` or using Poetry)
2. Ensure you have Python ≥ 3.11
3. (Optional) Use a virtual environment
4. Run experiment scripts in `experiments/` to reproduce results from the paper

## Usage

* To train or evaluate models under the preference-based conformal approach, use the scripts in `experiments/`.
* The notebooks provide step-by-step walkthroughs of key results and comparisons.
