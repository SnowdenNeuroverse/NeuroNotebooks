# NeuroNotebooks

This repository contains template and example notebooks for use in Neuroverse.

The templates can be loaded into your Notebooks session using the NeuroJulia function get_notebook

For example:
To load the NotebookAdminCommands.ipynb notebook found in this repository.

  - open a Julia Notebook in your Neuroverse Notebooks session
  - run the following code
    - using NeuroJulia
    - NeuroJulia.get_notebook("jl_NotebookAdminCommands")

This function will load the jl_NotebookAdminCommands.ipynb notebook into a folder called "00_NeuroTemplates" and add the current DateTime to the name.

# Basic Commands
### NotebookAdminCommands
This notebook shows how to see what Notebook sessions are active in your tenant and the user that they belong to.
 - [jl_NotebookAdminCommands](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_NotebookAdminCommands.ipynb)

### SchemaManagerCommands
This notebook shows how to deploy create a new schema for a db table and deploy it in Neuroverse
 - [jl_SchemaManagerCommands](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_SchemaManagerCommands.ipynb)

### AccessDataFromNeuroSql
This notebook shows how to access Neuroverse sql data in a Notebook
 - [jl_AccessDataFromNeuroSql](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_AccessDataFromNeuroSql.ipynb)
 - [py_AccessDataFromNeuroSql](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/py_AccessDataFromNeuroSql.ipynb)

# Helper Notebooks
### Endpoint Log Query
This notebook shows how to query the logs of a Neurovese Endpoint
 - [jl_EndpointLogQuery](https://github.com/SnowdenNeuroverse/NeuroNotebooks/blob/master/Notebooks/jl_EndpointLogQuery.ipynb)
