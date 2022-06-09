# The Zillow Project

## Project objectives

  - Document code, process (data acquistion, preparation, exploratory data analysis and statistical testing, modeling, and model evaluation),
  findings, and key takeaways in a Jupyter Notebook report.
  - Create modules (acquire.py, prepare.py) that make my process repeateableand your report (notebook) easier to read and follow..
  - Ask exploratory questions of my data that will help me understand more about the attributes and drivers of home value. Answer the questions by using charts and statistical tests.
  - Construct a model to predict assessed home value for single family properties using regression techniques.
  - Deliver a 5 minute target-audience-appropriate presentation consisting of a high-level notebook walkthrough using my Jupyter Notebook from above.
  - Answer questions of my audience.
## Business Goals
  - Construct an ML Regression model that predict propery tax assessed values ('taxvaluedollarcnt') of Single Family Properties using attributes of the properties.
  - Find the key drivers of property value for single family properties.
  - Deliver a report that the data science team can read through and replicate, understand what steps were taken, why and what the outcome was.
  - Make recommendations on what works or doesn't work in prediction these homes' values.
## Audience
  - My (virtual) customer/end user is the Zillow data science team.
## Project Deliverables
### A github repo containing the following:
  - A Readme (.md) file
    * A project description with goals
    * An initial hypotheses and/or questions you have of the data, ideas
    * A data dictionary
    * A project planning (lay out your process through the data science pipeline)
    * An instructions or an explanation of how someone else can reproduce your project and findings (What would someone need to be able to recreate your project on their own?)
    * The key findings, recommendations, and takeaways from your project.
  - A Final Report (.ipynb)
    * A Report that has filtered out all the extraneous elements not necessary to include in the report.
    * Use markdown throughout the notebook to guide the audience.
    * My notebook will begin with a project overview and goals and end with a conclusion that talks about your original goals and how you reached those (or didn't), the key findings, recommendations and next steps.
    * My work will include at least 4 visualizations in the form of:
        a. Question in markdown that you want to answer
        b. The 4 visualization
        c. At least 2 statistical tests
        d. Responses in natural language to the questions in my exploration phase
    * My work will include my 3 best models in the final notebook to review. It will show the steps and code I went through to fit the models, evaluate, and select.
    * On my best model, I will try to provide a chart visualizing how it performed on test.
  - Acquire & Prepare Modules (.py)
    * It will contain functions to acquire, prepare and split my data.
    * My work will be reproducible by someone with their own env.py file.
    * Each of my functions will be complimented with docstrings.
    * My functions to acquire and prepare my data will be imported and used in my final report
  - My project will also have 1+ non-final Notebooks (.ipynb) created while working on the project
### A final presentation
## Project Context
  - Dataset used came from Codeup database
  - The project is the first of the Modeling project
## Executive Summary - Conclusions & Next Steps
  - The goal of this project was to build a model that could predict whether a client would churn based on the previous data
  - Only classification models were used (Decision tree, Random Forest, K-Nearest Neighbor, Logistic Regression)
  - Findings:
    * The best model with the features used is the Decision Tree model.
    * Its accuray is 76%  compared to the baseline at 73%
    * Some features prevent churn and are worth examining
