# cookiecutter Simple DS project

A simple cookiecutter to stucture your Data Science projects.

to get started,

1. `pip install cookiecutter`
2. `cookiecutter https://github.com/Badr-MOUFAD/cookiecutter-simple-DS-project.git`


## Template structure

```
|
├── data                                <- where to put and save 
|   |── dataset1.csv                       your data
|   |
|   |──
│
├── notebooks_exploration_cleaning      <- notebooks related to data
|   |── exploration_1.py                   exploration and cleaning
|   |
|   |──    
│
├── notebooks_models                    <- notebooks to train
|   |── model_1.py                         and evaluate models
|   |
|   |──                                                           
│
├── py_scripts                          <- where to put repetitive code
│   ├── __init__.py                        
|   |
|   |── script_1.py
|   |
|   |──
│
├── README.md                           <- where to describe your project
|
├── .gitignore                          <- where to mention folder and files 
|                                          to not to be synchronazied 
|                                          with the remote repository
|                                           
└── environment.yml                     <- project dependencies
                                           (Anaconda environment)
```


## Note:

An **article** about the cookiecutter will be soon released. There, I will discuss the motivations behind building the cookiecutter, describe its structure, and state reasons of adopting it.

> In progress...