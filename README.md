
# Task: Disaster-Tweets-Classifications
## Natural Language Processing with Disaster Tweets
### Highlights:
  - This is a **Binary-class text classification (sentence classification)** problem.
  - The goal of this project is to **Predict which Tweets are about real disasters and which ones are not **.
  - This model was built with **ML CLassifierRandom Forest s** on **SKlearn**.

### Data: [Kaggle Dataset for Diaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/data)
  - Input: **Train.csv**
  - Output: **submision.csv**
  - Examples:


id	keyword	location	text	target
0	1	NaN	NaN	Our Deeds are the Reason of this #earthquake M...	1
1	4	NaN	NaN	Forest fire near La Ronge Sask. Canada	1
2	5	NaN	NaN	All residents asked to 'shelter in place' are ...	1
3	6	NaN	NaN	13,000 people receive #wildfires evacuation or...	1
4	7	NaN	NaN	Just got sent this photo from Ruby #Alaska as ...	1

### Python Libraries Used:
- Pandas
- Numpy
- Seaborn
- Matplotlib
- NLTK
- SKlearn
    
### Accuracy:
  - ACCURACY :  0.8010505581089954

### CONFUSION MATRIX:
![image](https://user-images.githubusercontent.com/11420101/164510186-6480d48e-c2eb-41f5-b1a7-454fcd841cbe.png)

### CLASSIFICATION REPORT::
 
               precision    recall  f1-score   support

           0       0.77      0.93      0.85       886
           1       0.87      0.62      0.72       637

    accuracy                           0.80      1523
   macro avg       0.82      0.78      0.78      1523
weighted avg       0.81      0.80      0.79      1523

