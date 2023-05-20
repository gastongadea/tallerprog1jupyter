# Jupyter Notebooks Basics and Python Exercises

## Introduction
In this assignment, you will learn the basics of Jupyter Notebooks and practice your Python programming skills with a set of beginner-level exercises. Jupyter Notebooks are a popular tool for interactive computing and data analysis. They allow you to create and share documents that contain live code, equations, visualizations, and explanatory text.

To complete this assignment, you will need to install Jupyter Notebooks on your computer. The installation instructions provided below will guide you through the process on Windows, Mac, and other operating systems. Additionally, you will fork a repository on Git and submit your assignment by making a pull request.

## Installation Instructions
Follow the instructions below to install Jupyter Notebooks on your operating system:

### Windows
<details>
  <summary>Installation in Windows</summary>
1. Install pip by downloading the [get-pip.py](https://bootstrap.pypa.io/get-pip.py) file and running it with Python.
2. Follow the instructions in the Jupyter notebook site, and install Jupyter using pip:
``` 
pip install notebook
```
3. Run the following command in the command prompt to start a new Jupyter session:
```
jupyter notebook
```

**Make sure not to install JupyterLab**, what you need is Jupyter Notebook. If you have installed JupyterLab, you can uninstall it by running the following command:
```
# Uninstall jupyterlab in case you downloaded it
pip uninstall jupyterlab
```

</details>

### Mac
<details>
    <summary>Installation in Mac</summary>

#### Through pip

1. Install pip by downloading the [get-pip.py](https://bootstrap.pypa.io/get-pip.py) file and running it with Python.
2. Follow the instructions in the Jupyter notebook site, and install Jupyter using pip:
```
pip install notebook
```
3. Run the following command in the command prompt to start a new Jupyter session:
```
jupyter notebook
```
**Make sure not to install JupyterLab**, what you need is Jupyter Notebook. If you have installed JupyterLab, you can uninstall it by running the following command:
```
# Uninstall jupyterlab in case you downloaded it
pip uninstall jupyterlab
```

#### Through Brew

1. Install [Homebrew](https://brew.sh/) by following directions in the brew website.
2. Install Jupyter Notebook using the following command:
```
brew install jupyter
```
3. Run the following command in the command prompt to start a new Jupyter session:
```
jupyter notebook
```
</details>

### Other Operating Systems
For other operating systems (e.g., Linux), you can follow the general installation instructions available on the [Jupyter documentation](https://jupyter.org/install) website.

## Forking the Repository
To get started with the assignment, you need to fork the assignment repository on Git. Follow the steps below to fork the repository and set up your own copy:

1. Visit the assignment repository on Git https://github.com/FacultadDeIngenieria/tallerprog1jupyter
2. Click on the "Fork" button in the upper right corner of the repository page.
3. Wait for the repository to be forked to your Git account.
4. Once the forking process is complete, you will be redirected to your forked repository.
5. You can now clone the repository (**the one associated to your GitHub Account**) to your local machine and start working on the assignment.

## The Assignment

There's a pre-existing jupyter notebook file, you need to make a copy of it before starting.

The copy must be named `firstname_lastname.ipynb` with firstname being your actual firstname and lastname your actual firstname. If you are named Juan Perez, the file should be named `juan_perez.ipynb`.

The assignment needs to be performed in that copy file, there's an export needed to be performed during the assignment, but other than the copy jupyter notebook and a pdf, **no additional files should be created or added**.

All the instructions and exercises are in the notebook file, you can open it with Jupyter Notebook and start working on it.

Here's a checklist in case you aren't sure what to do:

- [ ] Fork the repository
- [ ] Clone the repository to your local machine
- [ ] Install Jupyter Notebooks
- [ ] Create a copy of the notebook file and rename it.
- [ ] Open the notebook file with Jupyter Notebooks
- [ ] Complete the exercises in the notebook file
  - [ ] Make sure to save your changes
  - [ ] Make sure to run your code to check for errors
  - [ ] Make sure that EXERCISE 1 is finished
  - [ ] Make sure that EXERCISE 2 is finished
  - [ ] Make sure that EXERCISE 3 is finished
  - [ ] Make sure that EXERCISE 4 is finished
  - [ ] Make sure that EXERCISE 5 is finished
  - [ ] Make sure that EXERCISE 6 is finished
- [ ] Commit and push your changes to your forked repository
- [ ] Create a pull request to submit your work
- [ ] Wait for the pull request to be reviewed and merged by the assignment maintainer

## Completing the Assignment
To complete the assignment, you will work with Jupyter Notebooks and solve a set of Python exercises. Follow the steps below:

A pull request is a way to submit your changes to the original repository. Once you have completed the assignment, you will need to create a pull request to submit your work. Follow the steps below to create a pull request:

1. Go to the assignment repository on Git from your GitHub account.
2. Click on the "Pull Request" button in the upper right corner of the repository page.
3. Make sure the "base repository" is the one you forked in the previous section, and points to the branch `2023`.
4. Make sure the "head repository" is the one associated to your GitHub account.
5. Click on the "Create pull request" button.
6. Add a title with your firstname and lastname, and a description to your pull request with any concerns or questions you may have about the assignment.
7. Click on the "Create pull request" button to submit your work.
8. Wait for the pull request to be reviewed and merged by the assignment maintainer.