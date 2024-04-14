# Parkinson's Mouse Trail Microbiome Analysis using QIIME2, 

[QIIME 2™](https://qiime2.org) is a next-generation microbiome bioinformatics platform

## Steps to Run
1. Create a Conda Environment - if it does not exist yet
```shell
conda env create -name qiime2-dev --file qiime2-amplicon-macos-latest-conda.yml
```
2. Activate Conda environment 
```shell
conda activate qiime2-dev
```
3. Install QIIME and Dependencies: Install QIIME and its dependencies within the same conda environment.
```shell
conda install -c bioconda qiime2
```
4. Install Jupyter Support for QIIME: Install the Jupyter support for QIIME.
```shell
conda install -c conda-forge jupyter_contrib_nbextensions

```
5. Enable the QIIME Extension for Jupyter: Enable the QIIME extension for Jupyter within your conda environment.
```shell
jupyter serverextension enable --py qiime2 --sys-prefix
```
6. Start Jupyter Server 
```shell
jupyter notebook
```
7. After opening Jupyter in a Notebook , Create a cell and run 
```
!jupyter kernelspec list
```
output :
```
Available kernels:
  python3    /Users/fatimamubeenshaik/miniconda3/envs/qiime2-dev/share/jupyter/kernels/python3
```
