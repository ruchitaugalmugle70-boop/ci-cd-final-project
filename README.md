# cicd-final-project

This repository contains the final project for the Coursera course **CI/CD Tools and Practices**.

The project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions and OpenShift Pipelines.

## Usage

This repository contains the source code and configuration files for the CI/CD final project.

The project uses GitHub Actions to automate code linting and unit testing. OpenShift Pipelines is used to define the pipeline tasks for building and deploying the application.

**Repository name:** `cicd-final-project`

## Setup

After entering the lab environment, run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks

The project includes the following CI/CD pipeline tasks:

1. **Cleanup:** Clean up the source workspace before pipeline execution.
2. **Git Clone:** Retrieve the project source code from the GitHub repository.
3. **Linting:** Check Python code quality using Flake8.
4. **Unit Testing:** Execute automated unit tests using Nose.
5. **Buildah:** Build the application container image.
6. **Deploy:** Deploy the application to the OpenShift environment.

## GitHub Actions

The GitHub Actions workflow is located at:

`.github/workflows/workflow.yml`

The workflow automates code linting and unit testing when the configured GitHub events trigger it.

## OpenShift Pipelines

The Tekton task definitions are located at:

`.tekton/tasks.yml`

The pipeline configuration defines the tasks used for source retrieval, code validation, testing, container image building, and deployment.

## License

Licensed under the Apache License. See [LICENSE](/LICENSE).

## Author

Skills Network

<h3 align="center">© IBM Corporation 2023. All rights reserved.</h3>
