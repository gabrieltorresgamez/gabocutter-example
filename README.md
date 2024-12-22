# gabocutter-example

[![Build status](https://img.shields.io/github/actions/workflow/status/gabrieltorresgamez/gabocutter-example/main.yml?branch=main)](https://github.com/gabrieltorresgamez/gabocutter-example/actions/workflows/main.yml?query=branch%3Amain)
[![Commit activity](https://img.shields.io/github/commit-activity/m/gabrieltorresgamez/gabocutter-example)](https://img.shields.io/github/commit-activity/m/gabrieltorresgamez/gabocutter-example)
[![License](https://img.shields.io/github/license/gabrieltorresgamez/gabocutter-example)](https://img.shields.io/github/license/gabrieltorresgamez/gabocutter-example)

An example of a project generated with gabrieltorresgamez/gabocutter

- **Github repository**: <https://github.com/gabrieltorresgamez/gabocutter-example/>
- **Documentation** <https://gabrieltorresgamez.github.io/gabocutter-example/>

## Getting started with your project

### 1. Create a New Repository

First, create a repository on GitHub with the same name as this project, and then run the following commands:

```bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:gabrieltorresgamez/gabocutter-example.git
git push -u origin main
```

### 2. Set Up Your Development Environment

Then, install the environment with

```bash
make install
```

This will also generate your `uv.lock` file. You should commit and push this file.

You are now ready to start development on your project!
The CI/CD pipeline will be triggered everytime you push to the `main` branch.

## Structure

    ├── .github
    │   ├── actions        <- Github Actions configuration.
    │   └── workflows      <- Github Actions workflows.
    │   
    ├── gabocutter-example <- Source code for use in this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- MkDocs documentation for the project.
    ├── models             <- Modelcheckpoints, model predictions, metrics, and model summaries.
    ├── notebooks          <- Jupyter notebooks or Quarto Markdown Notebooks. 
    │                         Naming convention is a number (for ordering) and a short `-` 
    │                         delimited description, e.g. `00-example.qmd`.
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.    
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    ├── tests              <- Unit tests for the project.
    ├── .gitignore         <- Files to be ignored by git.
    ├── Dockerfile         <- Dockerfile for the Docker image.
    ├── LICENSE            <- MIT License.
    ├── Makefile           <- Makefile with commands like `make install` or `make test`.
    ├── mkdocs.yml         <- MkDocs configuration.
    ├── pyproject.toml     <- Package build configuration.
    ├── README.md          <- The top-level README for this project.
    └── uv.lock            <- Lock file for uv.