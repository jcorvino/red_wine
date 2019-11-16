# Red Wine Kaggle Competition
[![Red Wine Kaggle Competition](https://github.com/jcorvino/red_wine/blob/master/banner.PNG?raw=true)](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)
In this competition the quality of wine was predicted from a Kaggle wine dataset. The wine quality was given on a scale of 1-10, but the classification was used to determine whether wine is "good" or "bad". All wines with a quality score 7 or higher were deemed "good" and all other wines were deemed "bad". 
The original dataset was modified to convert wine quality to a "good/bad" rating. The strongest correlated property to wine quality was alcohol content (the higher the better) while the weakest correlated property was the residual sugar content. 

## Friendly Competition
For this competition, my friend Adam and I competed to get the best prediction score in 30 minutes. We used the Kaggle project shown [here](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009).

In the end, I had a precision score of 0.90 and Adam has 0.91, so he won (barely!). We both used gradient boosted random forest as a classification method, but he used more estimators, which lead to a better prediction.