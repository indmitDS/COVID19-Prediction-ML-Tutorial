# COVID-19 Prediction Model
A sample analysis on a small datset to analyze the causes and effects of COVID-19. A machine learning model has been trained on the dataset that predicts the death or recovery of a patient based on certain parameters.


Dataset has been used that consists of various attributes. Using these attributes, we try to find correlations so that proper analysis of the situation can be made. We have used Python programming language and various in-built libraries of python for the purpose of Data Mining and Analysis. 


Our system will consist of 5 stages: Data Preprocessing (Data cleaning, transformation and reduction), Encoding, Feature Selection, Visualization and finally Prediction. We have used logistic regression machine learning algorithm on the dataset and predicted the accuracy score by training the model. It would predict the chance of Death or Recovery of a patient depending upon the attributes (input variables).


We built this project with the purpose of analyzing the cause and effect of COVID-19. 



The dataset contains several parameters which were recorded based on the patients identified at different point of time. The parameters included are :


•	Reporting date – date of patient identified 


•	Location – location of patient 


•	Country – country in which patient is identified


•	Gender – gender of patient (Male-1, Female-0)


•	Age – age of patient


•	Visiting Wuhan – have the patient visited Wuhan in recent time


•	From Wuhan – is the patient from Wuhan


•	Death – does the patient died because of Covid-19 (0 or 1)


•	Recovered – does the patient recovered from Covid-19 (0 or 1)


Dataset - The dataset used in this notebook (Covid-19_dataset.csv) is same as the COVID19_line_list_data.csv dataset taken from https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset, with the only difference that in our dataset death and recovered columns contains values in the form of 0 or 1 and not in form of dates as in the later dataset.

