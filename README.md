## Rossman Kaggle Mini-Competition

The python version of our environment is 3.9.7

##Conda environment

Execute the following commands in the 'minicomp-rossman' folder:

conda create --name minicomp python=3.9.7
conda config --append channels conda-forge
conda activate minicomp
pip install -r requirements.txt

##Python script

Execute the script 'Compute_RMSPE.ipynb' in jupyter-lab. It will ask for
the address of the holdout csv file and compute the RMSPE value.
