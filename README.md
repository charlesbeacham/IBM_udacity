# IBM Project Udacity
Version 1.1

Summary of Project:

This project creates a recommendation engine in order to recommend articles to a user based on articles they have previously interacted with.  There is also an example of a potential cold-start method for new users with a custom created content recommendation.

### Table of Contents

1. [Installation](#installation)
2. [Instructions](#instructions)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

See environment.yml for full list of packages used.  The package manager used was conda and coded in Python 3.12.2.  THe main packages used were pandas, sci-kit learn, and nltk.

You can use the environment.yml to create an exact anaconda virtual environment with the command `conda env create -f environment.yml`

## Instructions <a name="instructions"></a>
No specific instructions for this project.

## Project Motivation<a name="motivation"></a>

For this project I was interested in demonstrating the following:
* Make article recommendations based on what articles a user has previously interacted with.
* Make article recommendations for new users who have never interacted with an article.
* Build a prediciton model using SVD to predict what article a user might interact with.

## File Descriptions <a name="files"></a>

* Recommendations_with_IBM.ipynb - this is the main notebook file containing the recommendation engine.
* Recommendations_with_IBM.html - this is a copy of the above file in html format.
* environment.yml - this is the list of packages used

## Results<a name="results"></a>

The recommendation engine predicted poorly due to low sample size of both the users and interacted articles.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Please feel free to use the code here as you like.
