# Profession Prediction
In the case of unlabelled data, we need to do unsupervised learning. But before we apply any clustering model, we must analyze the data first and decide which model is suitable.

## Dataset
The dataset that has been used here is the data of customers of a shop to update the policies accordingly. <br>
**Dataset**: [_Customer_](https://www.kaggle.com/datasets/datascientistanna/customers-dataset)

## EDA
EDA is one of the fundamental aspects before going into the model selection and working on that. So we analyze different behaviors and come to conclusions.

### Working Years vs Income
A strong **non-linear** relationship is seen in this case. We further divide this into two parts. We first check the behavior of people 
who worked less than 10 years, and people who worked more than 10 years. Detailed analysis will be found in the file. Here, only a sample is shown. <br>
<br><img width="724" height="503" alt="image" src="https://github.com/user-attachments/assets/95775843-d0a1-4211-a2f2-be3ef51d69f0" />
<br><br>
In this case, **Doctor** and **Artists** show steady and constant behavior in almost all period of working years. But other professions do the 
same, more or less. But in the case of people more than 10 years, the consistency only remains for **Artists** and **Doctor**. <br> <br>
<img width="716" height="506" alt="image" src="https://github.com/user-attachments/assets/1d34e9e4-0760-49ba-8ca4-7034d3992da7" />
<br> <br>

### Distribution of people across 9 fields
The overall count of females is more than male. Some are quite close. In the case of females, the homemaker, artist, and lawyer professions take the top positions. For 
males, Doctor, Executive, and Department take the top positions. <br> <br>
<img width="791" height="538" alt="image" src="https://github.com/user-attachments/assets/64d1d818-95e7-4ae3-943b-842e381d21b6" />
<br><br> 

### Spending habits
The interesting find was that family size does not affect the spending score that much. Overall, the median of spending scores has been analyzed, and the entertainment profession came out as the top one but others are very close and almost show an equal contribution towards the revenue. <br><br>
<img width="491" height="456" alt="image" src="https://github.com/user-attachments/assets/ed195433-6d69-43b7-b4d5-5b7fb4d43fb1" />
<br><br>


