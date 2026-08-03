# Machine Learning

- **ML**: is a subset of AI focused on *algorithms* that learn from date without explicit programming, involving feature engineering by practitioners.

- It includes various learning models: supervised(using labeled data), unsupervised(finding patterns without labels), semi-supervised(combining labeled and unlabeled data), and reinforcement learning(learning via interaction and feedback).

## Machine Learning Techniques

- **Classification**: predicts categories or classes
- **Regression**: predict continuous values
- **Clustering**: group similar date points for segmentation or pattern discovery.
- **Association**: finding co-occurring items.
- **Anomaly**: identifying unusual cases
- **Sequence mining**: predicting next event.
- **Dimensionality**: reduction and recommendation systems

## Application of machine learning

- In health care for diseases prediction
- Powering recommendation systems
- Bank use ML to assess loan risks, and telecom companies predict customer churn.
- Computer vision application in distinguishing pictures

## ML model lifecycle

- The lifecycle includes defining the problem, collecting data, preparing data, developing ad evaluating the model, and deploying the models.
- The process is iterative, meaning you may revisit earlier steps.

- **Problem Identification**

    Defining the problem clearly to align the solution with client needs.
    Collecting relevant data from various sources such as user demographics, purchase history, and product details.

- **Data Preparation and Exploration**

    Cleaning and formatting data to handle errors, missing values, and inconsistencies.
    Creating new features and performing exploratory data analysis to identify important patterns and correlations.

- **Model Development and Evaluation**

    Building models using techniques like content-based filtering and collaborative filtering.
    Evaluating model performance through testing, tuning, and gathering user feedback.

- **Deployment and Monitoring**

    Deploying the model as part of the product app and website.
    Continuously monitoring and updating the model to maintain and improve its effectiveness over time.

## Data scientist vs AI engineer on GAI

### Use cases

- **DSt**: focus on descriptive and predictive analytics, turning messy data into insight and forecasts using techniques like exploratory data
- **AIE**: works on prescriptive and generative use cases, building AI systems tha optimize decisions, create recommendation engines, intelligent assistants, and chatbots using foundation models.

### Data types

- **DSt**: primary use structured, tabular data that requires extensive cleaning and features engineering before modeling.
- **AIE**: mainly use large-scale unstructured data such as text, images, and audio to train foundation models like large language models(LLMs).

### Models and process

- **DSt**: use many specialized machine learning models tailored to specific tasks, which are smaller, faster to train, and less generalizable.
- **AIE**: use large, generalizable foundation models that require massive compute resources and training time but can handle diverse tasks without retraining.

*Data science involves training models from the scratch, while AI engineering leverages pre-trained models atd techniques like prompt engineering to build AI applications quickly*

## ML Tools

### Data and Machine Learning Tools

    Data consists of raw facts and figures that machine learning algorithms use to find patterns and make predictions.
    Machine learning tools support the entire pipeline, including data preprocessing, model building, evaluation, and deployment, simplifying complex tasks like big data handling and statistical analysis.

### Programming Languages for Machine Learning

    Python is the most popular language due to its extensive libraries and ease of use.
    Other languages include R (statistical learning), Julia (high-performance computing), Scala (big data processing), Java (scalable applications), and JavaScript (client-side ML models).

### Categories of ML tools

1    **Data Processing and Analytics Tools**: These tools help you handle and prepare your data before using it in machine learning. Think of them as kitchen tools that help you wash, chop, and organize ingredients before cooking a meal. Examples include:

*PostgreSQL*: A system to store and manage data like a digital filing cabinet.

*Hadoop and Spark*: Tools to process huge amounts of data quickly, like powerful machines sorting tons of ingredients.

*Pandas and NumPy*: Python libraries that help you clean, organize, and do math on your data easily.

2    **Data Visualization Tools**: These tools help you see your data in pictures like charts and graphs, making it easier to understand patterns. Imagine turning a recipe into a colorful picture to see what ingredients you need. Examples:

*Matplotlib and Seaborn*: Python libraries to create detailed and attractive charts.

*ggplot2*: A tool in R for building layered graphics.

*Tableau*: A software for interactive dashboards to explore data visually.

3    **Machine Learning Tools**: These are the core tools to build and improve machine learning models. They help you teach computers to find patterns and make predictions. Examples:

*Scikit-learn*: A Python library with many ready-to-use algorithms for tasks like classification and regression.

*SciPy*: Provides scientific computing functions to support machine learning.

4   **Deep Learning Tools**: These tools focus on neural networks, which are like computer brains that learn from data. They are great for complex tasks like recognizing images or understanding language. Examples:

*TensorFlow and Keras*: Libraries to build and train neural networks easily.

*PyTorch*: A flexible library for experimenting with deep learning.

*Theano*: Helps optimize mathematical calculations for deep learning.

5    **Computer Vision Tools**: These tools help computers "see" and understand images and videos. Imagine teaching a robot to recognize objects or faces. Examples:

*OpenCV*: A library for real-time image processing.

*Scikit-Image*: Offers image filters and feature extraction.

*TorchVision*: Provides datasets and tools for image tasks in PyTorch.

6   **Natural Language Processing (NLP) Tools**: These tools help computers understand and work with human language, like reading or generating text. Think of them as translators between humans and machines. Examples:

*NLTK*: A toolkit for processing text, like breaking sentences into words.

*TextBlob*: Simplifies tasks like sentiment analysis (detecting emotions).

*Stanza*: Offers accurate models for language tasks like tagging parts of speech.

7   **Generative AI Tools**: These tools create new content like text, images, or music based on input data. Imagine an artist painting pictures from your descriptions. Examples:

*Hugging Face Transformers*: Powerful models for text generation and translation.

*ChatGPT*: A language model that can chat and generate text.

*DALL-E*: Creates images from text descriptions.

*PyTorch*: Also used to build generative models like GANs for creating new data.

## Scikit-learn ML ecosystem

- Machine Learning Ecosystem Overview

    The ML ecosystem includes interconnected tools, frameworks, libraries, platforms, and processes for developing, deploying, and managing ML models.
    Python offers a rich ecosystem with libraries like NumPy, Pandas, SciPy, Matplotlib, and scikit-learn that support various stages of machine learning.

- Key Python Libraries for Machine Learning

    NumPy provides efficient numerical computations on large multidimensional arrays, forming the foundation for ML tasks.
    Pandas offers data analysis, cleaning, and preparation capabilities using data frames, while SciPy supports scientific computing and optimization.
    Matplotlib enables data visualization, and scikit-learn builds on these libraries to provide classical ML algorithms and utilities.

- Scikit-learn Features and Workflow

    Scikit-learn is a free, widely-used Python library offering classification, regression, clustering, and dimensionality reduction algorithms.
    It supports the entire ML pipeline including data preprocessing, model training, evaluation, hyperparameter tuning, and model export.
    A typical workflow involves data scaling, train-test splitting, model instantiation, training with fit(), prediction, evaluation with metrics like confusion matrix, and saving the model for production use.

## Definition and Types of Regression

- Regression is a supervised learning technique used to model the relationship between a continuous target variable and explanatory feature.

- Simple regression involves one independent variable predicting a dependent variable, while multiple regression uses more than one independent variable, both can be linear and nonlinear.

### Application of regression

- Regression is used to predict continuous values such as CO2 emissions from cars, sales forecasting, house prices, maintenance needs, and employment income.
- It's also applied in environmental science, public health, and other fields to estimate rainfall, wildfire risks, disease spread, and disease likelihood.

### Regression Algorithms

- Classic regression methods include linear and polynomial regression.
- Modern machine learning regression algorithms includes random forest, XGBoots, k-nearest neighbors, support vector machines, and neural neural network.

## Simple Linear Regression

- Simple linear regression models a linear relationship between one continuous target variable and a single explanatory future.
- It's used to predict a continuous value, such as CO2 emissions of a car, bases on one independent variable like engine.

### How Simple Linear Regression Works

    A best-fit line is determined through data points to represent the relationship between the independent variable and the target variable.
    The model is expressed as a linear equation with coefficients (theta zero as intercept and theta one as slope) calculated to minimize prediction errors.

### Model Evaluation and Calculation

    Residual errors measure the difference between actual and predicted values; the mean squared error (MSE) quantifies overall fit quality.
    Ordinary Least Squares (OLS) regression finds the line that minimizes the mean of residual errors using formulas derived by Gauss and Legendre.

### Advantages and Limitations

    OLS regression is easy to understand, interpret, and fast to compute, especially for small datasets.
    However, it may oversimplify complex relationships and is sensitive to outliers, which can reduce accuracy.

### Multiple Regression

    Multiple linear regression models the dependent variable as a linear combination of multiple independent variables with associated weights and an intercept term.
    The model can be represented mathematically using matrices for features and parameters.

Applications and Examples

    It can measure the effect strength of each independent variable on the dependent variable, such as predicting car CO2 emissions from engine size, cylinders, and fuel consumption.
    It is widely used in various fields, including education, to predict outcomes and analyze relationships between variables.

Model Building and Pitfalls

    Adding too many variables can lead to overfitting, where the model memorizes training data but performs poorly on new data.
    Categorical variables can be included by converting them into numerical or Boolean features.
    Correlated (collinear) variables should be handled carefully or removed to avoid misleading results.

Parameter Estimation and Prediction

    Parameters are estimated by minimizing the mean squared error (MSE) between predicted and actual values, commonly using ordinary least squares or optimization algorithms like gradient descent.
    The model can predict outcomes for new data points by plugging feature values into the linear equation.

Interpretation and Visualization

    For one feature, the model is a line; for two features, a plane; and for more features, a hyperplane.
    Multiple linear regression assigns relative importance to each feature based on the learned weights.

### Polynomial Regression

    Polynomial regression fits data using polynomial expressions of features by transforming the problem into a linear regression with new variables representing powers of the original feature.
    While polynomial regression can fit data well, very high-degree polynomials can overfit by capturing noise instead of underlying trends.

Nonlinear Regression

    Nonlinear regression models relationships using nonlinear functions such as exponential, logarithmic, or sinusoidal functions that cannot be reduced to linear regression.
    Examples include modeling exponential growth (e.g., GDP growth), logarithmic diminishing returns (e.g., productivity over hours worked), and periodic patterns (e.g., seasonal variations).

Model Selection and Optimization

    Visual analysis of scatter plots helps identify the type of relationship (linear or nonlinear) and guides the choice of regression model.
    Optimization techniques like gradient descent can be used to find the best parameters for a given nonlinear model, or machine learning models such as regression trees and neural networks can be applied when the model form is unknown.


### Logistic Regression Overview

    Logistic regression predicts the probability that an observation belongs to one of two classes, such as true/false or yes/no.
    It is suitable when the target variable is binary, when probabilistic outcomes are needed, and when understanding feature impact is important.

>Modeling and Decision Boundary

    Logistic regression uses a sigmoid function to map predictions to probabilities between 0 and 1, unlike linear regression which can produce unbounded values.
    A threshold (commonly 0.5) is applied to convert predicted probabilities into binary class assignments, defining a decision boundary.

>> Applications and Example

    Logistic regression can predict outcomes like customer churn, disease likelihood, or failure probability based on input features.
    For example, predicting customer churn using features such as age and account information, where the model outputs the probability of churn and classifies customers accordingly.

>Training Process of Logistic Regression

    Start with an initial set of parameters (theta), often chosen randomly.
    Predict the probability of class 1 for each data observation and measure the error using a cost function called log loss.

>Optimization and Cost Function

    Logistic regression uses a decision boundary created by combining a linear model with a sigmoid function.
    The goal is to minimize the log loss, which measures how well predicted probabilities match actual classes, penalizing confident but incorrect predictions.

>Gradient Descent Methods

    Gradient descent iteratively adjusts parameters in the direction of steepest descent of the cost function, controlled by a learning rate.
    Stochastic gradient descent (SGD) speeds up training by using random subsets of data, converging faster but with more variability, and can be improved by adjusting learning rate or sample size over time.
