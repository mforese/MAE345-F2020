# MAE345-F2020

Source code assignments for MAE345.

This repository contains Jupyter notebook assignments for Princeton's MAE345/549 class. It is organized in the following manner:

- All Jupyter notebooks are placed in the top level directory so they have access to all other Python modules and paths referenced in them are consistent.
- All data provided / collected for use in assignments resides in `data`.
- *Change:* The script `install_dependencies.sh` will install the necessary dependencies for running the software for the class on a fresh Ubuntu 18.04 installation. 
- *Depends on python3, git, jupyter-notebook, numpy, ... (add installation instructions/shell script)*

## Working on Assignments

To work on an assignment, open the `Terminal` application. Enter the command `cd MAE345-F2020` followed by the command `git pull`, which will update the code to the latest made available by the instructors. Then, enter `jupyter notebook`. This will open the Jupyter interface in your web browser, where you will work on your Python assignments. Then click on `LabX.py`, where `X` is the assignment number and fill out the specified cells in the notebook. Submission instructions are inside each notebook.

## Accessing New and Updated Assignments

Throughout the course, we will be adding more assignments to this Git repository. The instructors may also need to issue corrections to labs while they are assigned. To update the codebase on your computer, run the command `git fetch --all
 && git reset --hard origin/master` in the MAE345-F2020 folder (again, to get there enter `cd MAE345-F2020`). **THIS COMMAND WILL OVERWRITE THE ASSIGNMENTS YOU HAVE IN THE FOLDER.** If you want to backup an assignment, copy it to your home directory with the command `cp <filename> ~/` first.
