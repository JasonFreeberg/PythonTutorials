## [Data Science at UCSB](http://datascience.pstat.ucsb.edu/)

### Fall Quarter, 2016

### Introduction to Python for Data Science

### Instructor: [Jason Freeberg](https://www.linkedin.com/in/jfreeberg)

This quarter's tutorials will be the *best* yet! As you can see I've made a complete syllabus, a Jupyter notebook for each tutorial, and laid the [foundation](https://github.com/JasonFreeberg/StreamTweets) for your own personal projects. As the title says, we will learn the basics of Python for data science and data analysis. That includes OOP, the NumPy, pandas, and scikitlearn modules, feature engineering, and an introduction to machine learning. 

Every class will use a Jupyter notebook to show examples and illustrate new syntax. Then I will turn it over to you guys to finish on the exercises at the end of the notebook. The labs and notebooks are designed to *compliment* what you will learn online from DataCamp.com. To keep things moving each week, I will assume that you have finished last week's homework and are ready for the next set of material. **Now you might have some questions...**

*Why should I learn Python?* Well...
- It's a [popular](http://spectrum.ieee.org/static/interactive-the-top-programming-languages-2016) language.
- It's [very](http://www.kdnuggets.com/2015/05/r-vs-python-data-science.html) popular in the data science and analytics industries.
- You can use it to access [Spark's API](http://spark.apache.org/). 
    - Spark is a distributed computating framework built with support for SQL, streaming, and machine learning. 

*Are you qualified to teach this?* [Yes.](https://www.linkedin.com/in/jfreeberg#experience)
 - While interning at Impact Radius, I wrote PySpark code to analyse massive data sets (PySpark = Python + Spark).
 - I like to write Python code in my free time. We'll use one of my Python projects as the foundation for your own.
 - Python is **not** a hard language to learn... or teach!

---

#### Class requisites:
- Basic programming knowledge or concurrently taking a programming class
    - Or quickly complete the Codecademy [Python course](https://www.codecademy.com/learn/python). 
- Accounts for the following wesbites:
    - [DataCamp](https://www.datacamp.com/)
        - $9.00/month for student version
	- [Kaggle](https://www.kaggle.com/)
        - Good source of fun datasets
	- [Github](https://github.com/)
        - So you can get the tutorial notebooks

#### Week 1: “Welcome”
- Club information night! Ask questions, sign up, and pay dues
- Homework: 
	- Download and install [Python](https://www.python.org/downloads/), [PyCharm](https://www.jetbrains.com/pycharm/download/), and [Anaconda](https://www.continuum.io/downloads)
		- Download the right versions for **your OS**
        - If you get stuck just Google *"How to install ____".* Get good at phrasing your questions effectively.
        - Feel free to use a different editor.
	- Clone the [tutorial repository](https://github.com/JasonFreeberg/PythonTutorials) to your computer
        - Here's [a guide](https://www.youtube.com/watch?v=0fKg7e37bQE) to basic GitHub commands, I suggest against using the GUI.

#### Week 2: “Getting Started with Python”
- First tutorial session
- Get everyone set up with Python, PyCharm, Anaconda
- Using Jupyter Notebooks [in browser](http://jupyter.readthedocs.io/en/latest/running.html#running)
- Using [pip](https://packaging.python.org/installing/) and [conda](http://conda.pydata.org/docs/using/pkgs.html) to install modules
- Python Basics: syntax, objects, classes, modules, and data structures
- Homework:
    - *Optional:* [Codecademy course](https://www.codecademy.com/learn/python)
    - DataCamp: **Intro** to Python for DS: **Classes 1, 2, 3**

#### Week 3: “Tabular Data, Your New Best Friend”
- Practice loading a .csv file
    - With the help of pd.read_csv( )
- Handle missing values
    - And *wrong* values
- [Conditional selection](http://pandas.pydata.org/pandas-docs/stable/indexing.html)
- Homework:
    - DataCamp: **Intro** to Python for DS: **Class 4**
    - DataCamp: **Intermediate** Python for DS: **Class 1**

#### Week 4: “Basics of Prediction”
- Machine learning at a high level
- Types of machine learning
    - [Supervised](https://en.wikipedia.org/wiki/Supervised_learning) / [Unsupervised](https://en.wikipedia.org/wiki/Unsupervised_learning)
    - [Classification](https://en.wikipedia.org/wiki/Statistical_classification) / [Regression](https://en.wikipedia.org/wiki/Regression_analysis)
- Recent industry trends
    - Distributed computing overtakes single supercomputers
    - Common languages
- Examples with sci kit learn
- Homework:
    - DataCamp: **Intermediate** Python for DS: **Classes 2, 3**

#### Week 5: “Feature Engineering”
- Creating new columns
    - [Standardization](https://www.biomedware.com/files/documentation/Preparing_data/Why_standardize_variables.htm)
    - [Variable interaction](https://en.wikipedia.org/wiki/Interaction_(statistics))
- Mutating existing columns
- [Lambda functions and mapping](http://www.python-course.eu/lambda.php)
- Fill out course evaluations
- Homework:
    - DataCamp: **Intermediate** Python for DS: **Classes 4, 5**

#### Weeks 6 to 9: Begin Mini Projects
- Introduction to the data and possible project directions
    - Script streams Tweets into a MongoDB, list, or pandas Dataframe
    - Word cloud, sentiment analysis, geo-tag visualizations, network visualizations
- Or, find and plan your own project
	- Use meeting time to get help and input
