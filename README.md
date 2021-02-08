# Deep-COVID: Predicting COVID-19 From Chest X-Ray Images Using Deep Transfer Learning

We present Deep-COVID , a keras (python3) based implementation, to identify COVID-19 cases from X-Ray images. The model takes as input a chest X-Ray image and outputs the probability scores for 2 classes (NORMAL, COVID-19).

## Dataset
Deep Covid  uses the covid-chest xray-dataset for COVID-19 X-Ray images  a Kaggle dataset and a chest X-Ray Drop box dataset.
Dataset No 1 : https://www.dropbox.com/s/9w8nmj791c9ogsx/data_upload_v3.zip?dl=0
Dataset No 2 : https://www.kaggle.com/nabeelsajid917/covid-19-x-ray-10000-images

### Data Distribution
Chest X-Ray image distribution
|  Type | Normal | COVID-19 | Total |
|:-----:|:------:|:---------:|:--------:|
| Train |  70 |   28 | 98 |
| Val   | 70 |    28 |  98|

## Get started
Please refer our paper Deep-COVID: Predicting COVID-19 From Chest X-Ray Images Using Deep Transfer Learning for description of architecture and method. 

## Results

We present the results in terms of both the per-class AUROC (Area under ROC curve)  graphs showing model accuracy and loss, as well as confusion matrix formed by treating the most confident class prediction as the final prediction. We obtain a mean AUROC of `0.9738` (2-class configuration).

<center>


![Original 1](./assets/confusion.png,"Confusion Matrix") 



</center>
