# cicd-final-project

This repository contains the final project for the Coursera course **CI/CD Tools and Practices**.

## Usage

This repository contains the project files used to implement and demonstrate a CI/CD workflow using GitHub Actions and OpenShift Pipelines.

The project includes automated code linting, unit testing, container image building, and application deployment.

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

The project includes the following CI/CD tasks:

- **Cleanup:** Clean up the source workspace.
- **Git Clone:** Retrieve the project source code.
- **Linting:** Check code quality using Flake8.
- **Unit Testing:** Run automated unit tests using Nose.
- **Buildah:** Build the application container image.
- **Deploy:** Deploy the application to OpenShift.

## License

Licensed under the Apache License. See [LICENSE](/LICENSE).

## Author

Skills Network

<h3 align="center">© IBM Corporation 2023. All rights reserved.</h3>
