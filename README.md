# Module 2 - Asurion Client Project

This repository will serve as the home repo for the Blue Pandas (Team 9) Module 2 project for the Spring 2023 section of Data Science Teamwork in Practice.

### Prerequisites
To most easily run this code out of the box, the following packages must be installed:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* statsmodels
* imblearn
* datasets
* xgb

# Quick navigation
[Goals](#goals)  
[Background](#background)  
[Data](#data)  
[Models](#models)  
[Timeline](#timeline)  
[Repo Structure](#repo-structure)   
[Contact](#contact-info)

# Goals

* Goal 1: Complete a project that is helpful in projecting iPhone 14 claims for our client, Asurion.
* Goal 2: Identify current trends in Asurion's iPhone 14 claims that can be helpful in projecting future trends.
* Goal 3: Utilize the agile workflow as a team effectively to better learn how to function in a real-world project setting.
* Goal 4: Maintain a clean, informative Github repository as practice for future real-world projects.
* Goal 5: Maintain team cohesiveness and reduce team biases, such as groupthink and shared information bias, by communicating frequently and effectively.
* Goal 6: Leverage and understand each team members’ strengths and weaknesses to complete the project.

# Background  

The main vision of this project is to build a forecasting model to predict iPhone 14 claims for March, 2023. This model will be based on data provided by the client, Asurion. The overall goal for the model is to help Asurion discover new ways to reduce costs and optimize inventory, as well as gain real-world experience working in a team setting.

# Data

Due to the signed NDA as a part of the project, we will not go in detail about the data. However, we will mention that the data was provided by the client Asurion.

## Counts

The data consists of 26,661 rows and 5 columns. Once again, we will not delve in to the details of the data beyond this, as we signed an NDA.

# Models

The models built will be a combination of time-series, tree-based, and regression models, with the variable of interest being iPhone 14 claims. 

Evaluation metric: The best model will be determined by the Weighted Mean Average Percentage Error (WMAPE).

# Timeline

Start Date: 2/15/23  
End Date: 4/19/23

# Repo Structure 

The repo is structured as follows: Notebooks are grouped according to their series (e.g., 10, 20, 30, etc) which reflects the general task to be performed in those notebooks.  Each notebook is also susequently placed in the folder that is most appropriate for its purpose.  Start with the *0 notebook in the series and add other investigations relevant to the task in the series (e.g., `11-cleaned-scraped.ipynb`).  If your notebook is extremely long, make sure you've utilized nbdev reuse capabilities and consider whether you can divide the notebook into two notebooks.

All files which appear in the repo should be able to run, and not contain error or blank cell lines, even if they are relatively midway in development of the proposed task. All notebooks relating to the analysis should have a numerical prefix (e.g., 20-) followed by the exploration (e.g. 20-explore-data). Any utility notebooks should not be numbered, but be named according to their purpose. All notebooks should adhere to literate programming practices (i.e., markdown writing to describe problems, assumptions, conclusions) and provide adequate although not superfluous code comments.

# Contact Info

Tiffany Lee (tiffany.lee@vanderbilt.edu)  
Sruthi Pappu (chandrakantha.s.pappu@vanderbilt.edu)  
Kit Connelly (cristian.c.connelly@vanderbilt.edu)  
George Lyu (zhaozhou.lyu@vanderbilt.edu)  
