# Stock-Price-Prediction
This project uses different Deep learning as well as Machine learning algorithms with sentiment analysis to predict the stock prices.

## Algorithms Used
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Convolutional Neural Network (CNN)
- CNN-LSTM hybrid
- Bidirectional LSTM (Bi-LSTM)
- CNN-BiLSTM hybrid
- Gated Recurrent Unit (GRU)
- Support Vector Machine (SVM)
- Random Forest (RF)


## Sentiment Analysis
Sentiment analysis has been applied in the project in 2 different ways.
- Firstly, Sentiment analysis in applied on web scraped data from different stock related websites.
- Secondly, Sentiment analysis is applied on a dummy data based on twitter(because twitter API is now paid) to show the application of our project.


## Working
We have taken historical dataset form yahoo finance about bitcoin. After the data is preprocessed, all the models are trained on the data. Further web scraping is used to collect all the news about our stocks and the data is preprocessed and by using a dictionary-based sentiment analysis approach we find our postive and negative sentiment of the web scraped data. Similarly, sentiment analysis is applied to the dummy data giving the positive and negative sentiment providing the adjusted price accordingly.


## Pre-requisites
- Use Google collab or Jupyter Notebook.
- Accordinly what you are using, install the libraries as in the code.
