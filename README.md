# NeuroNotebooks

This repository contains template and example notebooks for use in Neuroverse.

The templates can be loaded into your Notebooks session using the NeuroJulia function get_notebook

For example:
To load the NotebookAdminCommands.ipynb notebook found in the Admin folder of this repository.

  - open a Julia Notebook in your Neuroverse Notebooks session
  - run the following code
    - Pkg.clone("https://github.com/SnowdenNeuroverse/NeuroJulia.git") #This only needs to be run once in a session
    - using NeuroJulia
    - NeuroJulia.get_notebook("NotebookAdminCommands")

This function will load the NotebookAdminCommands.ipynb notebook into a folder called "00_NeuroTemplates" and add the current DateTime to the name.
