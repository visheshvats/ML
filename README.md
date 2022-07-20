# **Author: Vishesh Vats**
# **Stock Market Prediction using Numerical and Textual Analysis**



Gmail: https://www.visheshvats021@gmail.com

LinkedIn: https://www.linkedin.com/in/vatsvishesh/

GitHub: https://github.com/visheshvats

In this task I tried to create a hybrid model for stock performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines.

## Approach:
Extract Sentiment Scores from given newspaper headlines data, with the help of nltk's SentimentIntensityAnalyzer


I have used stack LSTM (Long Short-Term Memory), to model the temporal effects of past events(both Textual, i.e the sentiment scores and Historical stock data) on opening prices

Achieved Training loss:0.0014  and Validation loss:0.0028 

Achieved RMSE on the Test data :20.1858 


## References:
Deep learning for stock prediction using numerical and textual information- Ryo Akita, Akira Yoshihara, Takashi Matsubara, Kuniaki Uehara





## Datasets:


Historical stock prices: https://finance.yahoo.com/


Textual News Headlines: https://bit.ly/36fFPI6
