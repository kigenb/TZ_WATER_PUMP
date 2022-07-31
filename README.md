# TANZANIA WATER PROJECT

![tz](https://user-images.githubusercontent.com/104420862/182042133-3288d84a-f3d8-4d68-b752-8b0060f93123.jpg)

## INTRODUCTION
Tanzania is a developing country based in East Africa Region that still has struggles with providing clean water to its entire population. There are many water points already established in the country, but some are in great need of repair while others have failed altogether.

## BUSINESS UNDERSTANDING
As an employee of the NGO I have been task to build machine learning models thats predict the functionality of all ground water pumps found throughout the country of Tanzania.If models are accurate, this could help save the Tanzanian government a lot of time and money.Accurate models can help to cut the cost on needing workers drive out to every water pump to inspect them.The government can use this study to know exactly which pumps are working, need repair and which ones aren’t working at all.

## DATA SOURCE
This project was for a competition on datadriven.org. The website describes itself as:
"DrivenData works on projects at the intersection of data science and social impact, in areas like international development, health, education, research and conservation, and public services."
The Taarifa Platform is an open source API designed to use citizen feedback on local problems. The competition and the data can be found at the link below:
https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/.

## METHODS
Data cleaning-replacing of missing values, changing of some values to integers and strings Exploratory Data analysis techniques Modelling-Use of Decision trees, Random forest and Knearest neighbours.

## RESULTS
Random forest was the best model for the analysis with an accuracy of 0.80 and f1 scores of 0.90, 0.28, and 0.77.Lo.The confusion matrix shows the discrepancy between the Random Forest's predicted status group label for a given pump vs the true status group label.The results of the random forest model are shown below;

    precision    recall  f1-score   support

           0       0.79      0.90      0.84      9523
           1       0.61      0.28      0.39      1290
           2       0.84      0.77      0.80      6896

    accuracy                           0.80     17709
   macro avg       0.75      0.65      0.68     17709
weighted avg       0.80      0.80      0.79     17709

## RECOMENDATION
Population: Population was one of the most important features in the random forest classifier. Analysis showed that pumps in lower population areas may be more likely to be non functional or needing repairs. The government should focus resources on low population areas, as they may not be receiving enough.
 Location:Based on the analysis, pumps in lower altitude areas may be more likely to need repair or be non functional. The government should focus resources on lower altitude pumps.
 
