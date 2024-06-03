# Demo of EBSD/TKD analysis with kikuchipy/HyperSpy at NNUM 2024

This repository contains the Jupyter notebook making up the demonstration of kikuchipy and HyperSpy at the Nordic Nanolab User Meeting (NNUM) in Oslo, Norway in June 2024.

kikuchipy is a library for analysis of electron backscatter diffraction (EBSD) patterns in Python, built on the tools for multi-dimensional data analysis provided by the HyperSpy library.
Tutorials and a complete description of all functionality is available at https://kikuchipy.org.

## Installation

Python packages required to run the notebook are listed in `requirements.txt`.
We recommend to use Python 3.10 and to create a new [conda environment](https://docs.conda.io/en/latest/miniconda.html) for this demo:

```bash
conda create --name kp-nnum python=3.10
conda activate kp-nnum
pip install -U -r requirements.txt
conda install nlopt  # Fails with Python 3.11 on macOS
```

Installation of packages and running of the notebook have been tested to work on a macOS with Apple Silicon with Python 3.10.
Further details on installation of kikuchipy and its dependencies are available in our [installation guide](https://kikuchipy.org/en/stable/user/installation.html).

## Validate installation

To validate the installation, launch Jupyterlab from the directory with the notebook file in your command line `jupyter-lab` and run the first cell of the notebook.
If no errors are showing, you're all good!

## Contact

If you have any issues with installation or questions related to the notebook, please reach out to Håkon W. Ånes (hwaanes@gmail.com).
