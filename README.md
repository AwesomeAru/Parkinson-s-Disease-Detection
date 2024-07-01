# Parkinson-s-Disease-Detection

### Description
Parkinson disease (PD) is a brain condition that causes problems with movement, mental health, sleep, pain and other health issues. PD gets worse over time. There is no cure, but therapies and medicines can reduce symptoms. Common symptoms include tremors, painful muscle contractions and difficulty speaking. Parkinson disease results in high rates of disability and the need for care. Many people with PD also develop dementia. The disease usually occurs in older people, but younger people can also be affected. Men are affected more often than women. The cause of PD is unknown but people with a family history of the disease have a higher risk. Exposure to air pollution, pesticides and solvents may increase risk.
Source : [WHO](https://www.who.int/news-room/fact-sheets/detail/parkinson-disease#:~:text=Parkinson%20disease%20(PD)%20is%20a,muscle%20contractions%20and%20difficulty%20speaking.)

### Project Description 
Using SVM (Support Vector Machine), this project will classify the input as either 
- Status = 1 i.e. has Parkinsons or
- Status = 0 i.e. does not have Parkinsons

The model acchieved 81.63% mean absolute error on validation data

The features considered by the model are :
- Average, Max and Min vocal fundamental frequency
- Several measures of variation in fundamental frequency
- Several measures of variation in amplitude
- Two measures of ratio of noise to tonal components in the voice
- Three nonlinear measures of fundamental frequency variation

Link for the dataset : [Kaggle](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)

![image](https://github.com/AwesomeAru/Parkinson-s-Disease-Detection/assets/93476957/3272b353-841d-4024-80fe-ab21b0dc4cc0)

![image](https://github.com/AwesomeAru/Parkinson-s-Disease-Detection/assets/93476957/d4a6f843-6dcf-4278-b44f-6edf997df700)



