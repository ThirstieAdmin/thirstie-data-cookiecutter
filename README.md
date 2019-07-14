# Overview

Project template for data analysis and ml projects.

To start a new project:

`> cookiecutter https://github.com/ThirstieAdmin/thirstie-data-cookiecutter`

and provide values for the prompt:
- project_slug:  A new repo name
- title: The name of project
- description: A short summary of the purpose of the project
- module_name: A valid python module name for the package that will contain the model.


### Prior art

This was inspired by Driven Driven's [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) but is meant to be more lightweight and flexible while preserving the following guiding principles:

- Data is immutable
- Notebooks are for communication and exploration
- Build from the environment up (i.e. you lose tons of time if you try to fit your project into an environment after the fact)
