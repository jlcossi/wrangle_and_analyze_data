# wrangle_and_analyze_data
Gather, Wrangle and clean WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

# Data Gathering, Assessment and cleaning process
The step by step is described in the report [wrangle_report.ipynb](wrangle_report.ipynb).   
You can also load this report through nbviewer with this [wrangle_report.ipynb](https://nbviewer.jupyter.org/github/jlcossi/wrangle_and_analyze_twitter_data/blob/master/wrangle_report.ipynb)

The main notebook containing all the gathering, assessment and cleaning is [wrangle_act.ipynb](wrangle_act.ipynb).  
You can also load it through nbviewer here : [wrangle_act.ipynb](https://nbviewer.jupyter.org/github/jlcossi/wrangle_and_analyze_twitter_data/blob/master/wrangle_act.ipynb)

# Installation
1. [Download and install Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html).
I suggest to select [Miniconda](https://docs.conda.io/en/latest/miniconda.html) which is quick and easy to install.

2. Install all the other dependencies using the "environment.yml" file included :
```
${HOME}/miniconda/bin/conda create -f environment.yml
```

3. Activate the new environment as suggested by conda
```
${HOME}/miniconda/bin/conda activate wrangling
```

4. launch jupyter using the notebook
```
$ jupyter-notebook wrangle_act.ipynb
```

