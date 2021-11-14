# cookiecutter Simple DS project

A simple template project to stucture your Data Science projects.

This template is inspired by "cookiecutter data science" to provide an entry-level structure to organize data science projects.

Check the following article to find out more about "Simple DS project", namely the motivation behind it as well as the purpose of every component of its structure.



## Getting started

to get started,

1. First, install cookiecutter by running
```
pip install cookiecutter
```

2. Then execute the following command to generate the project structure
```
cookiecutter https://github.com/Badr-MOUFAD/cookiecutter-simple-DS-project.git
```


## Template structure

After executing the previous commands, the project structure will be generated on your local machine.
The project directory contains the following directory tree


```
|
├── data                                <- where to put and save 
|   |── dataset_1.csv                      your data
|   |
│
├── notebooks_exploration_cleaning      <- notebooks related to data
|   |── exploration_1.py                   exploration and cleaning
|   |  
│
├── notebooks_models                    <- notebooks to train
|   |── model_1.py                         and evaluate models
|   |                                                        
│
├── py_scripts                          <- where to put repetitive code
│   ├── __init__.py                        
|   |
|   |── script_1.py
|   |
│
├── README.md                           <- where to describe your project
|
├── .gitignore                          <- where to mention folder and files 
|                                          to not to be synchronized 
|                                          with your remote repository
|                                           
└── environment.yml                     <- project dependencies
                                           (Anaconda environment)
```


## Note

This structure is not to be literally followed. You can adjust it and refine it based on your needs. Remember that the way you organize your work keeps evolving as you work on projects.

