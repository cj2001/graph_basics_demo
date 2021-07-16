# Graph Basics Demo Talk
### Written by: Dr. Clair Sullivan, Data Science Advocate, Neo4j
#### email: clair.sullivan@neo4j.com
#### Twitter: @CJLovesData1
#### Last updated: 2021-05-27

## Introduction

This repository contains the basic code and slides for an introduction to the basics of graphs, with a particular emphasis on data science.  

### How to run the code here

You will need to set up a Neo4j database and have access to Jupyter Notebook or JupyterLab.  There are many ways you can do this, but here are two recommended ways:

1. [Neo4j Sandbox](https://dev.neo4j.com/sandbox)

This link will create a free Sandbox database for you.  You will then need to make sure have 
installed the official Neo4j Python driver via `pip install neo4j`.  This will provide you with
a URI and a password for your database.  You can then create a Jupyter notebook and provides that
login information to the `Neo4jConnection` call in the intro.ipynb file.

2. Docker

If you want to run a pre-configured Jupyter notebook and Neo4j database on your local machine, 
you can follow the instructions at my blog post ["Get going with Neo4j and JupyterLab through Docker"](https://dev.neo4j.com/docker_neo_jupyter).  The repository for this post can be found [here](https://github.com/cj2001/data_science_neo4j_docker).  The only thing you will need to do then is to move the Jupyter notebook in this repo into the `notebooks/` subdirectory of that repository.  