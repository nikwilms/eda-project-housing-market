# Exploratory Data Analysis Project

Explore and analyze real estate data to gain insights into property market trends, pricing patterns, and influencing factors. This Exploratory Data Analysis (EDA) project offers an in-depth exploration of property attributes, prices, geographical distribution, and more. By visualizing data, identifying correlations, and examining patterns, this project aims to provide valuable insights that can inform investment decisions, guide renovation strategies, and understand market dynamics.

## Goals

- Conduct thorough exploratory analysis of real estate data.
- Visualize property market trends and patterns.
- Identify correlations between different property attributes.
- Investigate factors influencing property prices.
- Provide actionable insights for potential investors and homeowners.

## Requirements

- pyenv
- python==3.11.3
- Libraries: pandas, matplotlib, seaborn, numpy, folium

## Getting Started

1. Clone this repository to your local machine.
2. Set up a virtual environment using `pyenv` and install required packages using `pip`.
3. Explore the provided datasets and notebooks to understand the data and analysis.

## How to Use

1. Explore the Jupyter notebooks to understand the data preprocessing and analysis steps.
2. Visualize data trends using Matplotlib and Seaborn.
3. Analyze geographical distribution using Folium maps.
4. Gain insights from correlation matrices and visualizations.
5. Refer to the findings and insights for informed decision-making.

Enjoy your exploratory journey into the real estate market data!
## Setup

One of the first steps when starting any data science project is to create a virtual environment. For this project you have to create this environment from scratch yourself. However, you should be already familiar with the commands you will need to do so. The general workflow consists of... 

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

At the end, you want to make sure that people who are interested in your project can create an identical environment on their own computer in order to be able to run your code without running into errors. Therefore you can create a `requirements file` and add it to your repository. You can create such a file by running the following command: 

```bash
pip freeze > requirements.txt
```

*Note: In rare case such a requirements file created with `pip freeze` might not ensure that another (especially M1 chip) user can install and execute it properly. This can happen if libraries need to be compiled (e.g. SciPy). Then it also depends on environment variables and the actual system libraries.*

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

# License
This project is licensed under the MIT License.
