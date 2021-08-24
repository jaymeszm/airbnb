## Data Analysis of Airbnb listings in NYC

### Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Acknowledgements](#acknowledge)

### Installation <a name='installation'></a>
Running the linear regression models requires modules from scikit-learn (installation instructions [here](https://scikit-learn.org/stable/install.html)) and [statsmodels](https://www.statsmodels.org/stable/install.html). Other than that, the code uses standard Python libraries such as pandas, numpy, matplotlib, and seaborn, and should run with no issues on Python 3.*.

### Project Motivation <a name='motivation'></a>
Using Airbnb data on listings in New York City from August 2020 to August 2021, I wanted to understand:
- How do airbnb prices in NYC differ by neighborhood and other attributes?
- What are the most salient factors that predict pricing?
- How have prices trended during COVID-19?

### File Descriptions <a name='files'></a>
There are two notebooks that analyze 1) factors related to pricing, 2) price trends over time, as denoted by their titles. Each notebook contains markdown cells that walk through the exploration, visualiation, and model building step by step.

The 'data' folder contains monthly data downloaded from Airbnb.
The 'figures' folder contains all figures saved from the analysis. 

### Results <a name='results'></a>
The main results of this analysis can be found in this Medium [post](https://medium.com/@jaymeesheng/where-should-you-stay-in-new-york-bd6230714b29?source=friends_link&sk=db917983f89d41bb06fb8a34e4430eda).

### Acknowledgements <a name='acknowledge'></a>
The Airbnb data is available under a Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license and can be found [here](http://insideairbnb.com/get-the-data.html). 



