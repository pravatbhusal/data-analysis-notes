# Data Analysis References
A separate repository from my archives that contains all my data analysis studies and references.  

# Anaconda
Anaconda is a Python/R Data Science platform that automates many of the complicated tasks to set-up data science projects.
- https://www.anaconda.com/

Install Anaconda for your computer, and then set-up virtual environments (VMs) for projects that need specific dependencies.
- Anaconda comes with pre-installed dependencies for the ```root``` virtual environment such as scipy, jupyter, etc.

### Anaconda Package Manager
Anaconda's Package Manager is called ```conda```. Unlike Python's ```pip```, conda is best used for Anaconda.
- To update Anaconda's package manager, ```conda```, type ```conda update conda```
- To install Python packages on Anaconda, use ```conda install yourpackage``` instead of ```pip install yourpackage```
- To create a conda virtual environment, use ```conda create -n yourenvname python=x.x anaconda```
  - To enable the virtual environment, use ```source activate yourenvname```
