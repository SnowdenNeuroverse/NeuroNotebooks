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

## Available Notebooks
### [NotebookAdminCommands](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/NotebookAdminCommands.ipynb)
The notebook shows how to see what Notebook sessions are active in your tenant and the user that they belong to.

### [SchemaManagerCommands](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/SchemaManagerCommands.ipynb)
This notebook shows how to deploy create a new schema for a db table and deploy it in Neuroverse
