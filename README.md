EECS731
==============================

Introduction to Data Science 
Mini-Project 1: Clean and Combine Datasets using Pandas

This project served as an introduction to a typical data science workflow.
I utilized the cookiecutter data science project structure for the organization of this repository.
The main tools utilized in this mini-project were:
- Pandas (used to create dataframes and combine them into a singular dataframe)
- Jupyter Notebook (used to showcase my process)

My key learnings from this project are as follows:
1. Utilizing powerful data science frameworks for Python is essential to any successful data manipulation project. Without pandas, this project would have likely taken weeks to accomplish successfully (between developing algorithms to effectively combine data into useful dataframes to troubleshooting any major issues with actually importing data from CSV files). However, the tools provided by pandas made this project fairly simple to get working on, which will certainly come in handy down the line when the scope of the project increase beyond that of just data cleaning.
2. The Jupyter notebook is a great way of displaying the results of a data science procedure, but could also have applications in the software engineering field. Utilizing a notebook to show someone how your code will actually work ina clean, focused way makes talking about the code you have written much simpler. This also makes selling your solutions a little simpler too.
3. Cleaning data is a key aspect of the data science workflow. When I started looking at my raw data, I noticed that there were numerous rows that had effectively useless information for my purposes. It's important to make sure that our data frames are free from issues so that an effective data science workflow can be acheived, and no issues arise.
4. Initially, I was a little confused by the schema of the data I downloaded from AQUASTAT in that the main variables were actually stored in their own column, rather than as a table header. This approach actually makes a lot of sense from the perspective of a data scientist, since data can be selected by row while keeping the total number of columns in the dataset down. Actually organizing this into a table with this information as table could result in a dataset that is a little harder to swallow, since the number of columns would be massive. It is better to let the powerful software tools being utilized guide the procedure of data analysis than hapless manipulation with no clear goal in mind.

Overall, this project provided a good introduction to the data science workflow, and gave me confidence to move forward and look into new projects to work on. 

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
