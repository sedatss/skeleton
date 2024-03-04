# {{ cookiecutter.instance_name }}

Project for Frank applications deployed by JAR or Docker

<!-- TOC -->
* [Skeleton Project for Frank applications deployed by JAR or Docker](#skeleton-project-for-frank-applications-deployed-by-jar-or-docker)
  * [Introduction](#introduction)
  * [Included](#included)
  * [Usage](#usage)
    * [Steps](#steps)
    * [Template variables](#template-variables)
<!-- TOC -->

## Introduction

This project serves as a starting point for new projects or as example for existing ones.
This "empty" Frank! will have configuration files to build and deploy.
 
## Included

* Dockerfile
* Docker compose
* Publicode (WIP)
* GitHub Actions
  * Continuous Integration workflow
  * Release workflow

Please check if you deem all these functionalities necessary, if not remove them.

## Usage

### Steps

1. Clone or download this project
2. Find-and-replace the template variables listed in the [template variables](#Template variables) section
3. Add your own configuration files
4. Make sure that the GitHub action credentials are added
5. Commit & Profit!

### Template variables

| Template variable             | Description                                                                                    | Example        |
|-------------------------------|------------------------------------------------------------------------------------------------|----------------|
| `{{ cookiecutter.instance_name }}`            | The name of the Frank! to be deployed. It's best to keep this inline with the name of the repo | Frank2Skeleton |
| `{{ cookiecutter.instance_name_lc }}`         | Lowercase version of the instance name.                                                        | frank2example  |
| `{{ cookiecutter.configuration_name }}`       | The name of the first configuration (others have to be added manually)                         | Sans           |