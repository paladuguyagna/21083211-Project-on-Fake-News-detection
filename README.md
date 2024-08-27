**Exploring the Efficacy of Vectorization with Individual and Combined
Machine Learning Models for Fake News Detection**

**Overview**

This project, titled \"Exploring the Efficacy of Vectorization with
Individual and Combined Machine Learning Models for Fake News
Detection,\" focuses on detecting political fake news using various
machine learning models. The research evaluates the efficiency and
accuracy of different vectorization techniques (TF-IDF and Count
Vectorization) in conjunction with both individual models and hybrid
approaches, aiming to optimize the detection of political fake news in
internet sources.

**Objectives**

-   **Evaluate Linear Models:** Assess the performance of linear machine
    learning models like Logistic Regression, Passive Aggressive
    Classifier, and LinearSVC using different vectorization techniques.

-   **Boosting Models Analysis:** Investigate the effectiveness of
    boosting models (XGBoost, LightGBM, CatBoost) in fake news
    detection.

-   **Hybrid Model Exploration:** Explore the potential of hybrid models
    that combine linear and boosting techniques for improved accuracy
    and efficiency.

-   **Vectorization Impact:** Compare the impact of TF-IDF and Count
    Vectorization on model accuracy and detection speed.

**Features**

-   **Multiple Vectorization Techniques:** Implements both TF-IDF and
    Count Vectorization to convert text data into numerical form.

-   **Diverse Machine Learning Models:** Includes linear models,
    boosting models, and hybrid combinations for comprehensive analysis.

-   **Balanced Dataset Handling:** Utilizes SMOTE for addressing class
    imbalance in the dataset.

-   **Comprehensive Evaluation:** Provides detailed metrics including
    accuracy, precision, recall, F1-score, and model runtime.

**Installation**

1.  Clone the repository:

> bash
>
> Copy code
>
> git clone https://github.com/yourusername/fake-news-detection.git

2.  Navigate to the project directory:

> bash
>
> Copy code
>
> cd fake-news-detection

3.  Install the required dependencies:

> Copy code
>
> pip install -r requirements.txt

**Usage**

1.  Preprocess the data by running the scripts in the src/ directory.

2.  Train and evaluate models by executing the Jupyter notebooks in the
    notebooks/ directory.

3.  The results, including performance metrics and visualizations, can
    be found in the results/ directory.

**Data**

The dataset used in this project consists of political news articles
related to the Syrian conflict, sourced from Kaggle. The data includes
804 articles labeled as fake or credible. You can access the dataset
here: [[Kaggle
Dataset]{.underline}](https://www.kaggle.com/datasets/mohamadalhasan/a-fake-news-dataset-around-the-syrian-war).

**Contributing**

Contributions are welcome! Please follow these steps to contribute:

1.  Fork the repository.

2.  Create a new branch for your feature or bugfix.

3.  Commit your changes and push them to your branch.

4.  Create a pull request detailing the changes and improvements made.

