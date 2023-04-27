# Sentiment Analysis of IMDB Reviews using Naive Bayes

This project performs sentiment analysis on movie reviews from the IMDB dataset using the Naive Bayes algorithm. The goal is to build a classification model that can predict whether a given review is positive or negative. 

## Dependencies

This project requires the following dependencies:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- NLTK (Natural Language Toolkit)

You can install the dependencies using the following command:

```
pip install -r requirements.txt
```

## Dataset

The [IMDB dataset](https://ai.stanford.edu/~amaas/data/sentiment/) contains 50,000 movie reviews, out of which 25,000 are labeled as positive and 25,000 as negative. The dataset has already been preprocessed and is available in the `data` directory.

## Code

The `SentimentAnalysisOfIMDBmovieReviews.ipynb` file contains the code for preprocessing the data, feature extraction, training the Naive Bayes model, and evaluating the performance.

To run the code, follow these steps:

1. Clone the repository:

```
git clone https://github.com/SatyamJha2151/SentimentAnalysisofIMDBreviews_NaiveBayes.git
```

2. Change the current working directory to the project directory:

```
cd SentimentAnalysisofIMDBreviews_NaiveBayes
```

3. Run the `SentimentAnalysisOfIMDBmovieReviews.ipynb` file:

```
python SentimentAnalysisOfIMDBmovieReviews.ipynb
```

The program will train the Naive Bayes model on the training set and test it on the testing set. The performance metrics (accuracy, precision, recall, F1-score) will be printed to the console.

## Results

The performance of the model is as follows:

- Accuracy: 85.54%
- Precision: 86.35%

These results show that the Naive Bayes algorithm is effective in predicting the sentiment of movie reviews.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code as you see fit. Please see the LICENSE file for more details.

## Acknowledgments

This project is based on the [IMDB dataset](https://ai.stanford.edu/~amaas/data/sentiment/) and the Naive Bayes algorithm from the scikit-learn library. Special thanks to the creators of these resources for making them publicly available.
