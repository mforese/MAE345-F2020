# MAE345-F2020

Source code assignments for MAE345.

This repository contains Jupyter notebook assignments for Princeton's MAE345/549 class. It is organized in the following manner:

- All Jupyter notebooks are placed in the top level directory so they have access to all other Python modules and paths referenced in them are consistent.
- All data provided / collected for use in assignments resides in `data`.

## Install Instructions 

Included in this repository is a conda environment named `env-mae345.yml`. For the unfamiliar, [conda](https://docs.conda.io/en/latest/) (short for Anaconda) is a tool for managing Python environments --- collections of software and libraries for developing Python programs. Conda environments make it very easy to reproduce and share code with other developers (in this case between the students and AIs).

To install the environment, do the following:

1. Download and install [Anaconda](https://www.anaconda.com/products/individual).

2. On Mac and Linux, open the terminal. Navigate to where this repository has been downloaded (entering `ls` will list the files and directories accessible from your current directory and `cd <name>` will change you to the `<name>` directory) and run `conda env create -f env-mae345.yml`. Accept any of the prompted changes. On Windows, do the same, use the Anaconda terminal application that should be present in your start menu (on Windows you need to use `dir` to list the contents of a directory instead of `ls`).

## Working on Assignments

To work on an assignment, open the terminal (on Windows you need to use the same Anaconda terminal you used to install the environment) and navigate to the directory containing this repository. Enter the command `git pull`, which will update the code to the latest available by the instructors. Then, enter `jupyter notebook` or `jupyter lab`. These are two different interfaces for working with notebooks. The first is simpler, the second is newer and more featureful. Both commands will open the an interface in your web browser, where you will work on your Python assignments. Then click on `LabX.py`, where `X` is the assignment number and fill out the specified cells in the notebook. Submission instructions are detailed in the assignment PDF on Blackboard.

## Accessing New and Updated Assignments

Throughout the course, we will be adding more assignments to this Git repository. The instructors may also need to issue corrections to labs while they are assigned. To update the codebase on your computer, run the command `git fetch --all
 && git reset --hard origin/master` in the MAE345-F2020 folder (again, to get there enter `cd MAE345-F2020`). **THIS COMMAND WILL OVERWRITE THE ASSIGNMENTS YOU HAVE IN THE FOLDER.** If you want to backup an assignment, copy it to your home directory with the command `cp <filename> ~/` first.
