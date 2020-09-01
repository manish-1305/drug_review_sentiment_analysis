# Drug-Review-Sentiment-Analysis ..

This is the project to implement sentiment analysis of drug reviews, datasets came from UCI repository.
The project was implemented with Python and used Juypter as the developing tool . datasets.zip contains the datasets which are being used in this app .
In datasets.zip , the retrain file can be used as a sample retrain file , and the sample file can be used as sample file for bulk upload . 

=> we used nltk vader sentiment analyser to find thwe sentiment scores and and used 4 models to test i.e logistic regression, Multinomial NB, linear SVC, Random forest but
   the linear SVC gives the best accuracy its about 94%.
   
 => We used Flask,HTML,CSS to build the app and UI, Deployed it in AWS and Heroku Cloud.
 
 ### The application funtionalities are-
=> You can write your comment or review in the text box and predict it to get the Sentiment of the comment ,,
You can upload csv/excel file for bulk predictions,,
You can also download sample file for your reference,,
You can retrain the model with your dataset aswell .

Heroku app link :- https://drug-reviews-sentiment.herokuapp.com/

app demo- https://www.youtube.com/embed/vMi_nhBFwtI

## Final App UI

![image](https://user-images.githubusercontent.com/62827309/91665709-46a0b800-eb15-11ea-85f0-b85351f6e269.png)
