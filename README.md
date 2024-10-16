
# Virtual Drug Scanning with Gnina

This repository contains workflows and scripts for performing virtual drug scanning using molecular docking techniques. The primary focus is on using **Gnina**, a molecular docking software with built-in convolutional neural networks (CNNs) for predicting binding poses and binding affinities.

## Project Overview

The aim of this project is to automate the process of virtual screening for potential drug candidates against a target protein. By utilizing Gnina, the project predicts and scores ligand binding affinities, making it useful for drug discovery and development processes.

Key features of the project:
- Automated virtual drug scanning using molecular docking.
- Integration with Gnina for deep learning-based binding affinity predictions.
- Comprehensive analysis and visualization of docking results.

## Requirements

To run this project, you need the following dependencies installed:

- Python 3.8+
- Gnina (molecular docking software)
- Numpy
- Matplotlib
- Jupyter Notebook

You can install the required Python dependencies with the following command:

```
pip install -r requirements.txt
```

You will also need to install Gnina separately, which can be downloaded from the official [Gnina GitHub repository](https://github.com/gnina/gnina).

## Usage

1. Clone the repository:

```
git clone https://github.com/Jencheng1/VirtualScanning.git
cd VirtualScanning
```

2. Open the Jupyter notebook:

```
jupyter notebook virtual_scanning_gnina.ipynb
```

3. Follow the steps in the notebook to load your target protein and ligand structures, perform docking simulations using Gnina, and analyze the results.

## Data

The protein structure and ligands should be provided in PDB and SDF formats, respectively. These structures can be prepared using molecular modeling software or downloaded from databases such as the Protein Data Bank (PDB) and PubChem.

## Credit

This project utilizes **Gnina** for molecular docking and binding affinity prediction. Gnina enhances traditional docking methods with deep learning-based approaches to improve binding pose prediction and scoring accuracy.

## License

This project is licensed under the MIT License - see the LICENSE file at the following link for details: https://www.mit.edu/~amini/LICENSE.md.
