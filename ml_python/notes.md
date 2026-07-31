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
