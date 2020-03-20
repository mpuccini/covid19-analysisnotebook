# Covid-19 Simple Analysis Python Notebook

[![GitHub license](https://img.shields.io/github/license/mpuccini/covid19-analysisnotebook)](https://github.com/mpuccini/covid19-analysisnotebook/blob/master/LICENSE)

This is a simple Python notebook to analize data about italian Covid-19 plague. The dataset is linked (as a git submodule) to the institutional official data released by the italian *Protezione Civile* [repository](https://github.com/pcm-dpc/COVID-19.git).

## How it works?

Clone the repository and launch Jupyter:  
`jupyter notebook`  
Then choose the notebook and play!  
You might need some dependancies, you have them in the `environment.yml` file.  
You could create a virtual environment with pip referring to the dependacies in the environment.yml or, if you have conda (Anaconda or miniconda), create a new environment with just:  
`conda env create -f environment.yml`  
If you need more information about installing a conda distro, please refer to this [link](https://www.anaconda.com/distribution/) for Anaconda and to this [link](https://docs.conda.io/en/latest/miniconda.html) for miniconda.  

Once you have the environment with all the necessary dependancies, you have to activate it just typing:  
`conda activate covid19`  
then you can launch Jupyter as above.

> Please remember to update the data repository first of start analysing.
