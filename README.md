# Yelp Reviews Classification Project

This project is part of the Nebius Academy Machine Learning course, focused on building and evaluating a linear classification model. The goal is to predict Yelp review ratings based on the text of the reviews. 

## Dataset
We use a dataset of 650,000 Yelp reviews obtained from the Hugging Face library. The dataset contains text reviews and their corresponding ratings.

![Dataset](/Screenshot%202025-03-07%20at%2016.57.41.png)

## Tools and Libraries
- **Python**: Core programming language
- **Jupyter Notebook**: Interactive development environment
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Scikit-learn (sklearn)**: Machine learning algorithms and tools

## Workflow
1. **Load and explore the data**: Using Pandas and Matplotlibto inspect and understand the dataset.
2. **Preprocess the text data**: Tokenization and vectorization using `CountVectorizer`.
3. **Feature engineering**: Transforming text data into numerical feature vectors.
4. **Train-test split**: Using provided train and test subsets.
5. **Model training**: Training a logistic regression model with Scikit-learn.
6. **Model evaluation**: Using accuracy as the performance metric.


## Results
- Training accuracy: ~62%
- Test accuracy: ~59%

![Results](/Screenshot%202025-03-07%20at%2016.57.23.png)

