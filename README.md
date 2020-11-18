#  Cookiecutter Template: Jupyter Notebooks 

A [cookiecutter template](https://cookiecutter.readthedocs.io/en/1.7.2/) for simple data analysis based on
Chris Moffitt's [template](https://github.com/talkpython/pbp_cookiecutter).

## Folder structure

This template will jumpstart your data science projects with the following predictable organizational file structure:

```bash
.
├── Notebook.ipynb   # Data prep notebook
├── data               # Categorized data files
│   ├── external       # External data files  
│   ├── interim        # Working folder
│   ├── processed      # Cleaned and ready to use
│   └── raw            # Unmodified originals
└── reports            # Final reports
```

## Installation

To use Cookiecutter, you must have it installed along with Python 3. Once you have Python installed, the recommended way to install Cookiecutter is as follows. Install to the current user's folder, upgrade if available:

```bash
$ pip3 install -U --user cookiecutter
```

## Usage

Then in the folder you want to *contain* the project you're starting, run the template as follows, answering the questions as relevant to your project:

```bash
$ cookiecutter https://github.com/nuntz/jupyter_cookiecutter        
project_name [project_name]: My Data Project
directory_name [my_data_project]: 
description [More background on the project]: I need to analyze some data.
```

Now, in this example, we'll have a folder `my_data_project` with the structure described above ready to get to work.
