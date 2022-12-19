# Question-Answer-and-Finetuning-a-BERT-model-with-SQUAD-dataset


https://colab.research.google.com/drive/1Y5gV1W9hbIpz-_TafIiPKUC2VAHuoT_0?usp=sharing 

# Objective:

The objective of this ICP is to apply LSTM, LSTM-CNN, Bi-LSTM in dataset

# Approaches

A common dataset is analyzed with LSTM, LSTM-CNN, Bi-LSTM and efficiency is calculated

# Datasets

For dataset yelp_academic_dataset_review_100K.csv is used for Bi-LSTM analysis. yelp_academic_dataset_review_1M.csv is used for Use original labels instead of binary labels.

# Results:

Results are generated from tensorflow and sklearn and result is as below.
![image](https://user-images.githubusercontent.com/70243598/198187875-d466b6f5-02a2-4951-9f03-4a38e21d9bb7.png)

For the case of using original label, the result is as below:
![image](https://user-images.githubusercontent.com/70243598/198188105-92acc5ae-ad37-4c34-bd67-142cff04e825.png)

# Challenges

Using original label, efficiency is getting very low.

# Planned Work

For this ICP, the dataset is embedded, convert to binary and then analyzed with LSTM, CNN-LSTM, Bi-LSTM. Then analyzed without binarization 
and analyzed with LSTM and Bi-LSTM.  
