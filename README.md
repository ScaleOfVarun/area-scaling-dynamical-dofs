# Area-Scaling-of-Dynamical-Degrees-of-Freedom-in-Regularised-Scalar-Field-Theory

Jupyter notebook to reproduce the figures and numerical results of the paper “Area Scaling of Dynamical Degrees of Freedom in Regularised Scalar Field Theory.”

This repository accompanies the manuscript and provides the numerical experiments, data handling, and plotting routines used in the paper.
(https://arxiv.org/abs/2602.09100)

------------------------
## Repository contents

`area_scaling_num_expt.ipynb`
Main Jupyter notebook that runs the numerical experiments and generates all figures
appearing in the paper.

`data/`
Directory for input data and cached outputs used by the notebook.

Note: the data file `phi4_snapshots.npz`, which contains the data used to plot the relative projection error plot (Figure 1(b) of the paper), is not included in this folder due to its large size.

`figures/`
Output directory containing the generated figures (PDF format), matching those shown in the manuscript.

------------------------
## Usage

Open area_scaling_num_expt.ipynb.

Run the notebook cells sequentially. The cells allow you to generate the data file `phi4_snapshots.npz`, which is required to create Figure 1(b) in the paper. Please run the corresponding data generation cell, and the data gets saved in the data folder.

Figures are saved automatically to the figures/ directory.

------------------------
## Requirements

The notebook is written in Python and relies on standard scientific libraries (e.g. NumPy, SciPy, Numba, Matplotlib).
All dependencies are listed and imported directly in the notebook.

------------------------
## Citation

If you use this code, please cite the accompanying paper:

Area-Scaling of Dynamical Degrees of Freedom in Regularised Scalar Field Theory,
Oliver Friedrich, Kristina Giesel, and Varun Kushwaha
(https://arxiv.org/abs/2602.09100)


