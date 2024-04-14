# datathon_24
Code for UTA Datathon 24'



## Inspiration
Inspired by the growing challenge of online misinformation, we developed a machine learning model to identify check-worthy factual claims. This tool assists fact-checkers and promotes informed public discourse.

## What it does
Our model analyzes textual statements, distinguishing claims that warrant investigation from opinions or irrelevant content. We built it using a dataset of annotated statements, employing NLP techniques like lemmatization and TF-IDF to extract features, and training various machine learning algorithms.

## Challenges we ran into
Challenges included ensuring data quality, addressing subjectivity in "check-worthiness," and maintaining model interpretability. We're proud of achieving promising accuracy, building a robust pipeline, and gaining valuable insights into applying machine learning to fact-checking.
Data Quality and Bias: Ensuring the quality and representativeness of our dataset was crucial to avoid biased predictions. We addressed this by carefully selecting data sources and employing a rigorous annotation process.
Subjectivity: The concept of "check-worthiness" can be subjective, and there might not always be a clear-cut distinction between check-worthy and non-check-worthy statements. We mitigated this by establishing clear annotation guidelines and involving multiple annotators to reduce individual biases.
Model Interpretability: Understanding how the model makes its predictions is essential for building trust and identifying potential issues. We explored techniques like LIME and SHAP to explain the model's decisions and the importance of different features.

## How we built it
1. Data Collection and Annotation: We compiled a dataset of textual statements from various sources, including news articles, social media posts, and fact-checking websites. Each statement was manually annotated as either "check-worthy" or "not check-worthy" by human experts.

2. Data Preprocessing and Feature Engineering: We employed a range of natural language processing techniques to clean and prepare the text data, including:

3. Text normalization (lowercase conversion, punctuation removal)
Tokenization (splitting text into individual words)
Stop word removal (eliminating common, non-informative words)
Lemmatization (reducing words to their base form)
TF-IDF vectorization (representing text as numerical features based on word importance)
N-gram extraction (capturing word sequences for context)
4. Model Selection and Training: We experimented with various machine learning algorithms, including:

Logistic Regression
Support Vector Machines (SVM)
Random Forest
Gradient Boosting

5. Evaluation and Analysis: We evaluated the performance of our models using metrics such as accuracy, precision, recall, and F1-score. We also conducted error analysis to identify areas for improvement and potential biases.

## Accomplishments that we're proud of
Developing a functional fact-check worthiness classifier with promising accuracy.
Creating a robust data preprocessing and feature engineering pipeline.
Gaining insights into the challenges and opportunities of applying machine learning to fact-checking.

## What we learned
The importance of high-quality, unbiased data for building effective machine learning models.
The need for careful consideration of ethical implications and potential biases in model predictions.
The value of interdisciplinary collaboration between data scientists, NLP experts, and domain specialists.

## What's next for Innovative Data Intelligence Research Lab ML
Looking ahead, we plan to expand our dataset, explore advanced techniques like deep learning, incorporate domain knowledge, and develop user-facing applications to combat misinformation effectively.
