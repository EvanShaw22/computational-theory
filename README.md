# Assessment Submission for Computational Theory

This repository contains my submission for the module Computational Theory.
The project is written in a single Jupyter notebook, in Python.
Everything needed to run the notebook is included in this repository.

## Running the Notebook

In order to run `problems.ipynb` you can follow these steps:

1. Clone the repository using [git](https://git-scm.com/).
2. Ensure you have [Python](https://www.python.org/) installed. An easy installation of Python makes use of [uv](https://docs.astral.sh/uv/) or [Anaconda](https://www.anaconda.com/).
3. Create a virtual environment using either `uv` or Anaconda:
   - Using `uv`:
     ```bash
     uv venv
     ```
   - Using Anaconda:
     ```bash
     conda create --name problems python
     ```
4. Activate the virtual environment:
   - Using `uv`:
     ```bash
     source .venv/bin/activate
     ```
     On Windows:
     ```powershell
     .venv\Scripts\activate
     ```
   - Using Anaconda:
     ```bash
     conda activate problems
     ```
5. Install the required dependencies:
   - Using `uv`:
     ```bash
     uv pip install -r requirements.txt
     ```
   - Using Anaconda:
     ```bash
     pip install -r requirements.txt
     ```
6. Start JupyterLab:
   ```bash
   jupyter lab
7. Open `problems.ipynb` in JupyterLab and run the notebook cells.

## Dependencies

The notebook depends on the [IPython](https://pypi.org/project/ipython/), [ipykernel](https://pypi.org/project/ipykernel/), [JupyterLab](https://pypi.org/project/jupyterlab/), [Jupyter Notebook](https://pypi.org/project/notebook/), [NumPy](https://pypi.org/project/numpy/), [Pandas](https://pypi.org/project/pandas/), [SciPy](https://pypi.org/project/scipy/), [Statsmodels](https://pypi.org/project/statsmodels/), [yfinance](https://pypi.org/project/yfinance/), [Matplotlib](https://pypi.org/project/matplotlib/), [Seaborn](https://pypi.org/project/seaborn/), [Scikit-learn](https://pypi.org/project/scikit-learn/), [SymPy](https://pypi.org/project/sympy/), and [Pytest](https://pypi.org/project/pytest/) packages.

## About the Notebook

The Notebook relates to problems relating to Computational Theory.

## About the Author

I am a final-year student studying Computing in Software Development (BSc Hons) at [Atlantic Technological University (ATU)](https://www.atu.ie/) in Galway.
