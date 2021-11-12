#https://scanpy.readthedocs.io/en/stable/installation.html
#Installation

conda install seaborn scikit-learn statsmodels numba pytables
conda install -c conda-forge python-igraph leidenalg

#Development Version
##To work with the latest version on GitHub: clone the repository and cd into its root directory. To install using symbolic links (stay up to date with your cloned version after you update with git pull) call:

flit install -s --deps=develop  # from an activated venv or conda env
# or
flit install -s --deps=develop --python path/to/venv/bin/python 

#Don't try to use conda and beni to handle dependencies, it resulted in conflict and hardship in launch spyder 


##Python 3.9.7
##pip 21.2.4 from \spyderEnv\lib\site-packages\pip (python 3.9)
##conda 4.10.3