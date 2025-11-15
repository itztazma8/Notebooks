# Fake Bills Prediction
Predicting fake and real bills while collecting a huge amount of cash can be a difficult task when done manually. Hence, this is a machine learning approach to tackle the issue of predicting fake vs real bills. <br><br>
*Dataset*: [Fake bills](https://www.kaggle.com/datasets/alexandrepetit881234/fake-bills)
## Data Preprocessing
The dataset only had two columns. One was the serial numbers, and the other contained data regarding the note. From that data, the data was split, and then the necessary conversions were done. Then, we found the true labels and the other metrics, such as length, margin, and so on, for predicting.
## Model Selection
K-means clustering was used in this case. Using the elbow method, the number of clusters determined was **Two**. The prediction was done. The clusters were done well.
## Metrics
<img width="390" height="47" alt="image" src="https://github.com/user-attachments/assets/23605836-929e-4820-8e17-cff3b1025b82" />

The Silhouette score is around 0.34. The main reason behind this is that the numbers of metrics are too close to each other when it comes to fake or real bills. So when calculating the distance between a point of its own class and with respect to another class, the distance towards class 2 can be less. 
The accuracy score, when checked, ensures that the labels predicted were the right ones. <br><br>
**N.B: Now at times the result can be (1-0.99...) as labels- 0 and 1 are interchanged in many iterations.**
