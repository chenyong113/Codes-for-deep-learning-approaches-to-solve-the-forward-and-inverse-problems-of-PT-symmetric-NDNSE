# Codes for deep learning approaches to solve the forward and inverse problems of PT-symmetric nonlocal derivative nonlinear Schrödinger equations


## Description of the data and file structure

This is a project exploring deep learning approaches for solving the PT‑symmetric nonlocal derivative nonlinear Schrödinger equation.

All the codes have been tested on Windows machines with Miniconda  using TensorFlow 1.12.x. The following instructions allow users to run codes in this repo based on the Windows + Miniconda + TensorFlow 1.12.x system that has been used. However, in general, MacOS or Linux machines, with or without GPUs, should also work with slight modifications in the setup.

### Files and variables

#### File: NDNLSE_DeepLearning_codes.zip

**Description:** Codes for deep learning approaches to solve the forward and inverse problems of PT-symmetric nonlocal derivative nonlinear Schrödinger equations.

#### File: NDNLSE_E1_forward.py

**Description:** The code for deep learning methods to solve the forward problem of NDNLS equation with the PT-symmetric Scarf-II potential.

#### File: NDNLSE_E1_inverse.py

**Description:** The code for deep learning methods to solve the inverse problem of NDNLS equation with the PT-symmetric Scarf-II potential.

#### File: NDNLSE_E2_forward.py

**Description:** The code for deep learning methods to solve the forward problem of NDNLS equation with the PT-symmetric Rosen-Morse potential.

#### File: NDNLSE_E2_inverse.py

**Description:** The code for deep learning methods to solve the inverse problem of NDNLS equation with the PT-symmetric Rosen-Morse potential.

#### File: feijuyu

**Description:** The exact solution data for the NDNLS equation with the PT-symmetric Scarf-II potential obtained using MATLAB needs to be imported from this data file in the code.

#### File: feijuyu2

**Description:** The exact solution data for the NDNLS equation with the PT-symmetric Rosen-Morse obtained using MATLAB needs to be imported from this data file in the code.

<br />

## Code/software

| Software / Package | Version | Description                                                                                                                          |
| :----------------- | :------ | :----------------------------------------------------------------------------------------------------------------------------------- |
| Python             | 3.6.13  | Anaconda or Miniconda.                                                                                                               |
| TensorFlow         | 1.12x   | Open-source ML framework for neural network construction and training (TensorFlow 1.x API only, incompatible with TF 2.x by default) |
| NumPy              | 1.19.5  | Fundamental library for numerical computing and array operations                                                                     |
| SciPy              | 1.5.4   | Scientific computing library for MATLAB data import, interpolation and optimization                                                  |
| Matplotlib         | 3.3.4   | Visualization library for plotting results and generating figures                                                                    |
| pyDOE              | 0.3.8   | Library for generating Latin Hypercube Sampling (LHS) collocation points                                                             |
