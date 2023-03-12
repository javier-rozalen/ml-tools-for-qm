# Machine learning tools to solve the Schrödinger equation
![plot](assets/simple_ann.png)

## What is this repository?
It contains the code referred to in this [article](https://arxiv.org/abs/2205.12795). The repository contains a detailed PyTorch implementation of the method of *Neural Quantum States* for three different quantum systems, as a first resource for teaching purposes and also as a guide for those starting in the field. 

## Installation
To install this project in your computer, follow one of the following options:

### Option 1. conda  <img src="assets/anaconda.svg" alt="anaconda" width="20" height="20"/>
This option creates an isolated virtual environment containing all the necessary dependencies, which are automatically downloaded in the same version that was used to develop the original code, thereby ensuring reproducibility. Follow the steps below:

1. Clone the repository:

`git clone https://github.com/javier-rozalen/ml-tools-for-qm.git && cd ml-tools-for-qm`

2. If ```conda``` is not installed in your system, you can download it from https://docs.conda.io/en/latest/miniconda.html. 
3. Create a conda environment from the ```.yml``` file in the repository: 

`conda env create -f env.yml`

4. Activate the environment: 

`conda activate ml-tools-for-qm`

5. Install further requirements:

`pip install -r requirements.txt`

### Option 2. Docker   <img src="assets/docker.svg" alt="anaconda" width="20" height="20"/>


## Usage
There are three code files: 
* 1_harmonic_oscillator.ipynb
* 2_double_well.ipynb
* 3_hydrogen_atom.ipynb

They are all in the `.ipynb` format, designed to be open with Jupyter Notebook. To open each of them, run the command `jupyter notebook file.ipynb`, "file" being one of the three scripts in the list above. Each cell cell has been pre-run, so you should be able to see the outputs from the start, even before running the cells.

## Support
If you have any questions or issues, please contact us at jrozalen@ub.edu.
