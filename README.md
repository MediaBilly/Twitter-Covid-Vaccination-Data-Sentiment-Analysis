# Twitter-Covid-Vaccination-Data-Sentiment-Analysis

The purpose of this project is to do a sentiment analysis on tweets about covid19 vaccinations in 3 classes (0-neutral, 1-negative, 2-positive). 
Todo this, i experimented with 4 different types of models:

1. Softmax Regression
2. Feed-Forward neural network.
3. Bidirectional RNN neural network with LSTM & GRU cells (witout and with attention layer).
4. BERT-Base-uncased.

During the development of my models, i experimented with lots of different hyperparameters (as you can see in the notebooks) and rnn cells in the 3rd type.

The scores of the best models of each one of theese model types are listed below:

| Model       | Precision   | Recall        | F1 Score | Accuracy | 
| ----------- | ----------- | ------------- | ------ | ------- |
| Softmax Regression | 73.093% | 73.4%  | 72.967% | 73% |
| Feed-Forward neural network   | 73.479% | 73.794% | 73.424% | 73.79492% |
| LSTM neural network | 74.483% | 73.882% | 73.919% | 73.88256% |
| BERT-Base-uncased | 78.564% | 77.826% | 77.738% | 77.739% |

You can clearly see the increase of the scores when i increase the complexity of the used model (especially in BERT) because the statistical hypothesis in more complex models is usually more accurate.

The code in ipynb notebooks and data used can be found in the corresponding models.

Note: This project is a university assignment for the course Deep Learning for Natural Language Processing.
