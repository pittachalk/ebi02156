# ebi02156

This repository contains my code submission for the EBI02156 vacancy.

To run the code, I recommend installing required dependencies with Anaconda / Miniconda using the provided `env.yml` file.
```sh
# install environment
conda env create -f env.yml

# activate  environment
conda activate ebi02156
```

The code for the analysis is in a Jupyter notebook called `main.ipynb`. You can start a Jupyter server to interactively run the notebook. The following should open a Jupyter interface to access the notebook:
```sh
jupyter notebook
```

Alternatively, you can execute the notebook via the command line to produce the plots and a HTML file of the result. 
```sh
jupyter nbconvert --to=html main.ipynb --output=main.html --output-dir=plots/ --execute
```

