# JPX-IntroDS
### JPX Tokyo Stock Exchange Prediction Kaggle Challenge for CS3943

This notebook (`JPX_Prediction.ipynb`) tracks our exploration of Time-Series models applied to the stock market. The notebook is annotated for readability, and it contains insights that were discovered along the way. The data used was acquired from a past Kaggle competition: JPX Tokyo Stock Exchange Prediction https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction.

A brief synopsis of our work: 
<br />We discovered upon taking the first difference of our time-series that the data is essentially a white-noise process. As a result, we find that traditional time-series analysis methods are either not sophisticated enough or perhaps inappropriate for this particular problem. We would not be comfortable using these models to predict even a few days into the future, much less six months. We conclude that, in order to adequately address our original problem statement/question, we would need to explore far more sophisticated models and techniques. Such techniques include deep learning models, sentiment analysis alongside price history analysis, etc. 
