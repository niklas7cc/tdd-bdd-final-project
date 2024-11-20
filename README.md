This repository contains code and projects developed as part of the **IBM DevOps and Software Engineering Professional Certificate** on Coursera. The work here includes exercises, assignments, and projects that were completed throughout the course.

### Course Overview:
The **IBM DevOps and Software Engineering Professional Certificate** program is designed to teach the fundamental principles of DevOps, Agile methodologies, and software engineering practices. It covers topics such as version control, automated testing, continuous integration, and deployment.

### Repository Content:
- Various exercises and practical projects covering DevOps practices.
- Scripts and code examples related to the coursework.
- Resources used during the course.

### Usage:
Feel free to explore the repositories and adapt the code for your learning or project needs. If you have any questions or issues, please feel free to open an issue.

### Acknowledgements:
This project was completed as part of the **IBM DevOps and Software Engineering Professional Certificate** on Coursera. Special thanks to IBM and Coursera for providing the resources.
# TDD / BDD Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **Introduction to TDD/BDD**.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template. 

Name your repo: `tdd-bdd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks

In this project you will use good Test Driven Development (TDD) and Behavior Driven Development (BDD) techniques to write TDD test cases, BDD scenarios, and code, updating the following files:

```bash
tests/test_models.py
tests/test_routes.py
service/routes.py
features/products.feature
features/steps/load_steps.py
```

You will be given partial implementations in each of these files to get you started. Use those implementations as examples of the code you should write.

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

John Rofrano, Senior Technical Staff Member, DevOps Champion, @ IBM Research

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
