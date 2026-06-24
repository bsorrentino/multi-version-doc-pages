# Setup intructions

The goal of this project is to provide a proof of concept to evaluate feasibility of deployment to github pages of a multi version documentation.

## Technology stack

The tech stack must be based on use of `mkdocs` + `mkdocs-material` + `mike`. 
Use python virtual env `venv` to manage requirements.


## tasks

* Setup a simple documentation using `mkdocs` + `mkdocs-material` 
* Write github action to deploy multi version documentation using `mkdocs` + `mike`
* Write a version selector main page that allow to browse the deployed versioned documentation

## Versions management

I use `git flow` to manage branching strategy so i want that when i push `develop` branch this must be update the `dev` documentation release. If I create a new tag `v<version number>` this must be considered a new documentation number `<version number>

