# Jupyter Playground

The Jupyter Notebook Playground is a repository created to showcase a variety of experiments in data science and visualization. Using Jupyter notebooks as the primary tool, this repository serves as a platform for sharing knowledge and exploring the vast potential of data science. With a wide range of experiments and demonstrations, the Jupyter Notebook Playground provides an interactive and collaborative environment for users to engage with data science concepts and techniques

## How to Use Jupyter Notebook Playground?

To get started with Jupyter Notebook Playground, you will need to have [Jupyter Notebook environement installed](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) on your computer. Once you have installed your notebook environemnt, you can clone this repository to your local machine, install dependencies and start exploring the various notebooks available.

> git clone git@github.com:tobrun/jupyter-playground.git
> cd jupyter-playground
> pip3 install .

You can now open this project directory in VSCode.

## Env. variables

A variety of notebooks integrate in services that require access tokens for authentication. Depending on which you execute you will need to have the following env. variables provided:

> OPENAI_API_KEY

## Static code analysis

Install tools with
> pip3 install -e '.[lint]'

Run tooling with
> isort --check-only . -v
> black --check --diff . -v
> flake8 . -v
