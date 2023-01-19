# Blockchain-Project
## Sentiment Analysis using Naive Bayes, BERT and RoBERTa

### File Structure:
  * [Presentation.pdf](https://github.com/xandie985/Blockchain-Project/blob/main/Presentation.pdf): contains brief description of the work.
  * [sentiment analysis of cryptocurrency tweets_ NB, BERT, RoBERTa.ipynb](https://github.com/xandie985/Blockchain-Project/blob/main/sentiment_analysis_Naive_Bayes_%2C_BERT_%26_RoBERTa.ipynb): contains extensive work performed. 
  * [tweet_extraction_api.ipynb](https://github.com/xandie985/Blockchain-Project/blob/main/tweet_extraction_api.ipynb): uses Twitter dev API to extract tweets.
---
### Dataset: [Crycptocurrency Annotated Data](https://query.data.world/s/krdiofdnalp376rqwddoddzgryedt4)
  * The dataset contains around 50k+ Annotated tweets. 
  * The labels are unbalanced so, we balance the data by picking equal number of each sentiment. 
    * 5k Positive tweets
    * 5k Negative tweets
    * 5k Neutral tweets
 ---
### Steps:
  * Dataset cleaning
  * Removing NaNs
  * Balancing the dataset
  * Removing unnecessary words/names of Cryptocurrencies
  * Visualizing the data
  * Modelling
    * Naive Bayes method
    * BERT method
    * RoBERT method
  * Observations and conclusion
