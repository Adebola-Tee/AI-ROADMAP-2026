# AI Roadmap 2026

This repository documents my AI/ML learning journey.

## Week 1 Focus

The focus of Week 1 was setting up my learning environment, understanding beginner Python tools, and writing my first Python notebooks.

## Tools Used

- Python 3.12.2
- pip
- VS Code
- Jupyter Notebook
- JupyterLab
- Git
- GitHub

## What I Learnt This Week

- How to install and test Python
- How to use pip to install Python packages
- How to open and use Jupyter Notebook and JupyterLab
- The difference between code cells and Markdown cells
- How to use variables
- How to use `print()`
- How to use `input()`
- How to use `float()` and `int()`
- How to use f-strings
- How to push a project to GitHub

## Week 1 Notebooks

- Day 2: First tutoring income calculator
- Day 3: Python small exercises
- Day 4: Tutoring monthly income estimator
- Day 5: Personal monthly progress calculator

## Reflection

This week helped me build confidence with the basic tools needed for my AI/ML journey. I moved from installing tools to writing simple Python programs and pushing my work to GitHub.

## Week 2 Focus

This week, I practised Python basics including variables, strings, numbers, input, conditions, lists, and simple beginner projects.

## Week 2 Projects

- Temperature Converter
- BMI Calculator
- Student Grade Predictor
- Quiz Program
- Daily Task Tracker

## Week 3 Focus

This week, I started learning Python for data. I practised working with CSV files, pandas, DataFrames, selecting columns, filtering rows, sorting data, counting values, and creating simple reports.

## Week 3 Projects

- Pandas Introduction
- Pandas Data Selection
- Pandas Practice Exercises
- Student Class Report Generator
- Personal Tutoring Data Analysis

## Week 3 Skills Practised

- `pd.read_csv()`
- `.head()`
- `.info()`
- `.shape`
- selecting columns
- filtering rows
- `.sort_values()`
- `.value_counts()`
- `.sum()`
- `.mean()`
- `.max()`
- `.nunique()`

## Week 4 Focus

This week, I started learning the maths behind machine learning in a beginner-friendly way.

I focused on understanding:

- dataset
- features
- target/label
- prediction
- actual value
- error
- absolute error
- loss

## Week 4 Projects

- ML Story with Pandas
- ML Error Practice
- Understanding Model Predictions and Errors
- Tutoring Prediction Analysis

## Key Understanding

This week helped me understand that machine learning is not only about making predictions. It is also about comparing predictions with actual values and measuring how wrong the model is.

The error shows the difference between the actual value and the predicted value.

The loss gives a summary of how wrong the model is overall.

## Week 5: Data Storytelling

### Focus

This week, I learnt how to move from simply viewing data to explaining what the data means.

The focus was on:

- exploratory data analysis
- charts
- observations
- insights
- simple data storytelling
- mini data reports

### What I Practised

I practised using `pandas` and `Matplotlib` to explore and visualise data.

The main skills I used were:

- creating pandas DataFrames
- inspecting data with `head()`, `info()`, and `describe()`
- checking missing values with `isnull().sum()`
- calculating totals and averages
- creating bar charts
- creating line charts
- creating scatter plots
- interpreting chart patterns
- writing insights from data

### Week 5 Projects

- Data Storytelling Introduction
- Explore and Visualise Data
- Data Storytelling Practice
- Weekly Tutoring Data Analysis
- Personal Data Storytelling

### Key Concepts

A `bar chart` helps compare categories.

A `line chart` helps show change or trends.

A `scatter plot` helps show the relationship between two numerical values.

An `observation` is something I can clearly see from the data.

An `insight` explains what the observation might mean.

A `data story` combines data, charts, observations, insights, and decisions.

### Main Understanding

This week helped me understand that charts are not just for decoration.

A chart should help me answer questions such as:

- What does the chart show?
- What pattern can I see?
- Why might the pattern exist?
- What decision can I make from it?

### Reflection

Week 5 helped me move from basic data analysis into data storytelling.

I learnt that data becomes more useful when I can explain it clearly. I also learnt that different charts have different purposes, and choosing the right chart helps make the message clearer.

The most important thing I learnt this week is:

Data storytelling means using numbers, charts, and explanations to communicate a clear message.

## Week 6: Machine Learning Foundations

### Focus

This week, I started learning the foundations of machine learning.

I focused on understanding:

- features
- target/label
- training data
- testing data
- regression
- classification
- prediction
- model evaluation

### What I Practised

I practised creating small datasets and separating them into `X` and `y`.

`X` represents the features or input columns.

`y` represents the target or answer column.

### Week 6 Projects

- Machine Learning Foundations
- Features and Target
- Features and Target Practice
- Student Performance Dataset Preparation
- Tutoring Score Prediction Preparation

### Key Understanding

The biggest thing I learnt this week is that machine learning starts with a prediction goal.

The target is what I want to predict.

The features are the information available that can help predict the target.

I also learnt that regression means predicting a number, while classification means predicting a category.

### Reflection

This week helped me understand the first real structure of machine learning.

Before training a model, I must prepare the data properly by identifying the features and the target.

This made machine learning feel less abstract and more practical.

## Week 7: Classical Machine Learning Models

### Focus

This week, I moved from machine-learning foundations into my first classical machine-learning model.

I focused mainly on Linear Regression and learnt how a model can learn relationships from data and make predictions on new examples.

### What I Learnt

This week, I learnt about several classical machine-learning models:

- Linear Regression
- Logistic Regression
- Decision Trees
- Random Forests
- K-Nearest Neighbours

I also learnt that:

- Linear Regression predicts numerical values.
- Logistic Regression predicts categories.
- Decision Trees make predictions through a sequence of questions.
- Random Forests combine many decision trees.
- K-Nearest Neighbours makes predictions using similar examples.

### Linear Regression Practice

I spent most of the week practising Linear Regression.

I learnt the complete workflow:

`Data → DataFrame → X and y → create model → fit model → new data → prediction`

I used:

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X, y)
## Week 9: Feature Engineering

### Focus

This week, I learnt how to prepare raw and incomplete data before using it for machine learning.

The main topics were:

- missing values
- mean, median and mode
- deleting or filling incomplete data
- preparing a dataset for machine-learning use

### What I Learnt

I learnt that real-world datasets can contain missing values and that these missing values need to be handled carefully before training a model.

I practised:

- `isnull()` to find missing values
- `isnull().sum()` to count them
- `dropna()` to remove incomplete rows
- `fillna()` to replace missing values
- `mean()` for average numerical values
- `median()` for middle numerical values
- `mode()` for the most common categorical value

### Important Understanding

I learnt that there is no single correct way to handle every missing value.

The method depends on the type of data and the problem.

For example:

- mean can be useful for numerical data
- median can be better when extreme values may affect the average
- mode is useful for categorical data
- deleting rows can remove useful information, so it should not be done blindly

### Mini Project

I completed a missing-values mini-project where I:

- created a messy student dataset
- identified missing values
- created a copy of the original data
- filled missing numerical values
- filled categorical values
- checked that no missing values remained

### Personal Tutoring Application

I also applied the same feature-engineering ideas to a tutoring dataset containing:

- study hours
- attendance
- subject
- homework score
- final score

This helped me understand how data cleaning could be used in a realistic context before building a machine-learning model.

### Key Memory

The workflow I want to remember is:

Raw data
→ find missing values
→ decide how to handle them
→ fill or remove them
→ check again
→ clean dataset
→ ready for machine learning

### Reflection

Week 9 helped me understand that machine learning does not begin with model training.

The data has to be prepared first.

I now understand that feature engineering involves making thoughtful decisions about how raw data should be cleaned and transformed before a model learns from it.

The main idea I want to remember is:

**Good models need well-prepared data.**
## Week 11: Neural Network Intuition

### Focus

This week, I learnt the basic intuition behind neural networks.

The main concepts were:

- neurons
- layers
- inputs
- weights
- bias
- activation
- output
- backpropagation
- gradient descent

### What I Learnt

I learnt that a neural network takes inputs, processes them through neurons and layers, and produces an output.

I also learnt that the network improves by adjusting internal parameters such as weights and bias.

### Neural Network Structure

The basic structure is:

Input Layer
→ Hidden Layer(s)
→ Output Layer

The input layer receives the clues or features.

The hidden layers combine the information and learn useful patterns.

The output layer produces the final answer or prediction.

### Neurons

I learnt to think of a neuron as a small decision worker.

A neuron receives inputs, gives them different levels of importance, combines them, and produces a response.

### Weights

Weights represent how important each input is to the neuron.

A larger weight means that input has more influence on the neuron's calculation.

I also learnt that weights are learnable parameters.

The network can adjust them during training.

### Bias

Bias is an extra adjustment added to the weighted inputs before activation.

I learnt that bias is not another feature.

It is an internal parameter that helps adjust the neuron's calculation.

### Activation

The activation function takes the neuron's combined value and determines how strongly the neuron should respond.

The basic forward flow is:

Inputs
→ multiply by weights
→ add weighted inputs
→ add bias
→ activation
→ output

### Backpropagation

Backpropagation sends information about the prediction error backward through the network.

This helps determine which internal parameters contributed to the mistake.

### Gradient Descent

Gradient descent helps adjust the model's parameters in a direction that reduces the error.

The memory line I want to remember is:

**Backpropagation tells the network what needs adjusting. Gradient descent helps make the adjustment.**

### Practice

I practised:

- identifying inputs
- assigning weights
- calculating weighted inputs
- adding bias
- creating a simple activation function
- producing an output
- changing weights and observing how the output changed

### Personal Application

I applied the concept to a tutoring context using:

- attendance
- homework score
- previous test score

I created a simple neuron that used these inputs to produce a student-support response.

### Important Understanding

I now understand that the inputs are the information given to the network.

The weights and bias are internal parameters that can be adjusted.

The network learns by improving these internal parameters so future predictions become better.

### Key Memory

The full neural-network story I want to remember is:

Clues enter
→ neurons process them
→ weights control importance
→ bias adds an adjustment
→ activation produces a response
→ output gives a prediction
→ compare prediction with reality
→ backpropagation sends error information backward
→ gradient descent adjusts the parameters
→ the network tries again

### Reflection

Week 11 helped make neural networks feel much less abstract.

At the beginning, terms like neurons, activation, backpropagation and gradient descent sounded complicated.

By the end of the week, I was able to connect each term to a simple idea and build small neuron calculations myself.

I now understand the basic story of how a neural network processes information and learns.

The main idea I want to remember is:

**A neural network learns by adjusting its internal parameters so its predictions improve over time.**
```
