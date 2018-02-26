# NeuroNotebooks

This repository contains template and example notebooks for use in Neuroverse.

The templates can be loaded into your Notebooks session using the NeuroJulia function get_notebook

For example:
To load the NotebookAdminCommands.ipynb notebook found in this repository.

  - open a Julia Notebook in your Neuroverse Notebooks session
  - run the following code
    - Pkg.clone("https://github.com/SnowdenNeuroverse/NeuroJulia.git") #This only needs to be run once in a session
    - using NeuroJulia
    - NeuroJulia.get_notebook("NotebookAdminCommands")

This function will load the NotebookAdminCommands.ipynb notebook into a folder called "00_NeuroTemplates" and add the current DateTime to the name.

# Basic Commands
### NotebookAdminCommands
The notebook shows how to see what Notebook sessions are active in your tenant and the user that they belong to.
[jl_NotebookAdminCommands](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_NotebookAdminCommands.ipynb)

### SchemaManagerCommands
This notebook shows how to deploy create a new schema for a db table and deploy it in Neuroverse
[jl_SchemaManagerCommands](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_SchemaManagerCommands.ipynb)

### AccessDataFromNeuroSql
This notebook shows how to access Neuroverse sql data in a Notebook
[jl_AccessDataFromNeuroSql](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_AccessDataFromNeuroSql.ipynb)
[py_AccessDataFromNeuroSql](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/py_AccessDataFromNeuroSql.ipynb)

# Tutorials
## Available Julia Notebooks:

## Available Python Notebooks:
