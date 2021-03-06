<h1 align="left">:bar_chart: Startup's Success Analysis</h1>
<p align="left"><a href="https://github.com/quelcamara/startup-success-analysis"><img src="https://img.shields.io/badge/Languages-1-pink"></a> <a href="https://github.com/quelcamara/startup-success-analysis/commits/master"><img src="https://img.shields.io/badge/Last%20Commit-March-red"></a> <a href="https://github.com/quelcamara/startup-success-analysis"><img src="https://img.shields.io/badge/Project%20Status-Finished-lightblue"></a></p>

# Table of Contents
* [About the project](#computer-about-the-project)
* [Description](#gear-description)
* [Technologies](#hammer_and_wrench-technologies)
* [Setup](#rocket-setup)
  * [Requirements](#requirements)
  * [Installation](#wrench-installation)
  * [Executing via cmd](#game_die-executing-via-cmd)
* [Author](#superhero-author)

## :computer: About the project
This is a case study developed as the final project of a Data Science Bootcamp aiming to evaluate the progress of the course.

The main goal was to predict the profit of a new Startup based on certain features and deciding whether one should invest in a particular startup or not.

## :gear: Description
The project was divided into 6 sections and is provided with many notes regarding the author's interpretation and her initiation on data analysis. It also includes the .csv file and a directory where the plots were saved. You will see under the sections:

1. Project Definition:
   - [x] Study object
   - [x] Objective
   - [x] Additional Information
   - [x] Method

2. Exploratory Data Analysis (EDA):
   - [x] Importing/collecting data
   - [x] Data cleaning
   - [x] Data exploration
   - [x] Data preparation

3. Model Building:
   - [x] Splitting data
   - [x] Predictive modeling
   - [x] Decision Tree Regression Model
   - [x] Random Forest Regression Model
   - [x] Models score

4. Graphical Analysis
   - [x] Data Visualization
   - [x] Original data interpretation
   - [x] Predicted data interpretation
   - [x] Original vs. Predicted data 
   - [x] Models evaluation 
   
5. Linear Regression
   - [x] Linear Regression Model
   - [x] Model score and evaluation
   - [x] Original vs. Predicted data 
   - [x] Graphical Data Analysis
  
6. Conclusion
   - [x] Comparative table
   - [x] Model's scores and errors measurement

## :hammer_and_wrench: Technologies
This project was built with the following technologies:
* [Python](https://www.python.org/downloads/) --version: 3.7
* [Jupyter Notebook](https://jupyter.org/install) --version: 6.2.0
* [Pandas](https://pandas.pydata.org/) --version: 1.2.1
* [Numpy](https://numpy.org/) --version: 1.19.2
* [Matplotlib](https://matplotlib.org/) --version: 3.3.2
* [Seaborn](https://seaborn.pydata.org/) --version: 0.11.1
* [Scikit learn](https://scikit-learn.org/stable/) --version: 0.24.1

## :rocket: Setup
It will be necessary to have some basic configurations done on your machine to execute the project.

:bulb: You will not be able to either access or manipulate the project if you don't have your local server running the `Jupyter Notebook`.

### Requirements
Before you get started, you will need to have [Python](https://www.python.org/downloads/) installed on your machine as well as the [Jupyter Notebook](https://jupyter.org/install). There is no need to have any specific code editor or IDE if you wish to work on the code - you can do it directly on the notebooks.

Also, if you only want to snoop into the code and have no interest on changing it, you can skip directly to the topic [Executing via cmd](#executing-via-cmd) and forget about the [Installation](#wrench-installation).

Since it is not externally deployed, you will need to download the [startup-success-analysis](https://github.com/quelcamara/startup-success-analysis) project into your computer to be able to run it locally.

#### :wrench: Installation
If you have different versions of the technologies used to create this project, no need to panic! It won't be necessary to uninstall everything. You can always give it a try on running it on you machine with the current versions you already have and see if it works. If something goes wrong - because packages and functions are constantly being updated - you can easily create a virtual environment and then install only what you need.

You can follow the steps below if you need to create and configure a virtual environment. These are for Windows command-line, if you are a Linux or MacOS user, you will need to look for the likely commands. On the Command Prompt (cmd):

```shell
# Open the project directory (full path here)
$ cd C:\..\startup-success-analysis-master

# Create the virtual environment (choosing python 3.7)
$ virtualenv venv --python=python3.7

# Access the virtual environment
$ venv\Scripts\activate.bat
```
After that, you will see a `(venv)` sign on the command-line indicating that you are now inside the virtual environment. It should look like this:
```shell
$ (venv) C:\..\startup-success-analysis-master>_
```
Finally, you can install the technologies you need with whatever version you want inside your environment, and it won't affect at all any package you have on your operational system. Use the `pip install` for that:

> Just a friendly reminders here!<br/>
If you have installed <b>Anaconda</b> on your computer at any moment in your life, you probably already have all those packages available for you. Check for their versions and, if you have any troubles executing the Notebooks, create the virtual environment and install the packages using `conda` instead of `pip`.

```shell
$ pip install pandas==1.2.1
$ pip install numpy==1.19.2
$ pip install matplotlib==3.3.2
$ pip install seaborn==0.11.1
$ pip install scikit-learn==0.24.1
```
With these configurations, your machine is now ready to run and manipulate the project.

#### :game_die: Executing via cmd
To run the project and have access to the Notebooks:
```shell
# Go to the project directory (full path here)
$ cd C:\..\startup-success-analysis-master

# Open the directory on the Jupyter Notebook
$ jupyter notebook
```
Just be patient here if your computer takes a little while without seeming to do a thing at all. It will process your inquisition and then open an external page on the web (your default browser) running the server on your localhost. You don't need to enter anything else on the command-line until this page is opened.

## :superhero: Author
<img src="https://avatars3.githubusercontent.com/u/73648823?s=460&u=81cc56a7c802bd21b265dfb0dadadccce01ec987&v=4" height="100" width="100">
Raquel Câmara Porto :maple_leaf:

<a href="https://www.linkedin.com/in/raquel-camara/"><img src="https://img.shields.io/badge/-Raquel-%230077B5?style=flat-square&logo=linkedin&logoColor=white"></a> <a href="mailto:raquelc.porto@outlook.com"><img src="https://img.shields.io/badge/-raquelc.porto@outlook.com-%230078D4?style=flat-square&logo=microsoft-outlook&logoColor=white"></a>
