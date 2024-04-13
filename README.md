## Project Overview
In this project, we performed sentiment analysis on the IMDb movie review dataset using a logistic regression model. We followed the following steps:

1. **Data Preparation**: Loaded the IMDb movie review dataset and performed basic data preparation steps.
2. **Text Preprocessing**: Cleaned and preprocessed the text data by lowercasing, tokenization, removing special characters, stopwords, and performing stemming.
3. **Feature Extraction**: Converted the preprocessed text data into TF-IDF features.
4. **Model Selection**: Chose logistic regression as the classification algorithm.
5. **Model Training**: Trained the logistic regression model on the training data.
6. **Model Evaluation**: Evaluated the trained model using accuracy, precision, recall, and F1-score.
7. **Model Tuning (Optional)**: Fine-tuned the hyperparameters of the logistic regression model using grid search with cross-validation.
8. **Prediction**: Used the trained model to make predictions on new, unseen movie reviews.
9. **Conclusion**: Summarized the results of the sentiment analysis experiment and discussed insights gained from the analysis.

## Files
 `sentiment_analysis.ipynb`: Jupyter Notebook containing the code for the sentiment analysis project.
 `README.md`: This README file providing an overview of the project.

## Usage
To run the sentiment analysis project:

1. Clone this repository to your local machine.
2. Open and run the `sentiment_analysis.ipynb` notebook in a Jupyter Notebook environment.

## Dependencies
This project requires the following Python libraries:

`numpy`
`pandas`
`nltk`
`scikit-learn`

You can install the dependencies using the following command:
`pip install numpy pandas nltk scikit-learn`

## Author
**Oluwaseun Moses Adeniyi**

## License
This project is licensed under the MIT License - see the LICENSE file for details.
