# CAML/ELSA?
**E**nsemble **L**earning for classifying **S**ingle-cell data and projection across reference **A**tlases

## Contents
#### [Installation](https://github.com/linwang6/CAML#Installation)
#### [Tutorial](https://github.com/linwang6/CAML#Tutorial)
#### [Contact](https://github.com/linwang6/CAML#Contact)
#### [Copyright and License Information](https://github.com/linwang6/CAML#Copyright-and-License-Information)


## Installation
    Requiements:
    1. Python 2.7 or greater version
    2. Packages:
       numpy (>=1.8.2)
       scipy (>=0.13.3)
       scikit-learn (>=0.20) 
       pycm
       imbalanced-learn (0.4)
      
    How to install packages (Taking imbalanced-learn as example)?
    1. Imbalanced-learn is currently available on the PyPi’s reporitories and you can install it via pip. 
       It's easy to install packages using pip.
       For example, typing command: pip install -U imbalanced-learn to install 
       'imbalanced-learn' package.
    2. The package is release also in Anaconda Cloud platform.
       For example, typing command: conda install -c conda-forge imbalanced-learn to install 
       'imbalanced-learn' package.
    3. Or install using pip and GitHub.
       For example, typing command: pip install -U git+https://github.com/scikit-learn-contrib/imbalanced-learn.git 
       to install 'imbalanced-learn' package.
     
     
## Tutorial
    Please simply typing command: python caml.py
    It gives you help information for caml,
    Usage: python caml.py classification scell/snuc/bulk [-m] [-i] [-c] [-g] [-o] [-s]
       python caml.py projection     scell/snuc/bulk [-t] [-p] [-c] [-g] [-o] [-s]

    classification arguments:
     -m, --cell_marker       	   list for cell marker
     -i, --input_file        	   input data for classification
     -c, --cell_type         	   cell type list
     -g, --geneNum             	   number of top importances
     -o, --output            	   output file for cell types
     -s, --specify (optional)      specific cell type for extend, for example -s CD4:CD8

    projection arguments:
     -t, --traning           	   traning prep data
     -p, --prediction        	   prediction prep data
     -c, --cell_type         	   cell type list
     -g, --geneNum           	   number of top importances
     -o, --output            	   output file for cell types
     -s, --specify (optional)      specific cell type for t cell


#### Classification of single-cell data
    
    
#### Projection of single-cell/single-nuc data 
    
    
    
    
## Contact
    
    
    
## Copyright and License Information


