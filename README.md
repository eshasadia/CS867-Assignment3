# Deep-COVID: Predicting COVID-19 From Chest X-Ray Images Using Deep Transfer Learning
We present Deep-COVID , a keras (python3) based implementation, to identify COVID-19 cases from X-Ray images. The model takes as input a chest X-Ray image and outputs the probability scores for 2 classes (NORMAL, COVID-19).

 ## Introduction
Coronaviruses are a large family of viruses which may cause illness in animals or humans. In humans, several coronaviruses are known to cause respiratory infections ranging from the common cold to more severe diseases such as Middle East Respiratory Syndrome (MERS) and Severe Acute Respiratory Syndrome (SARS). The most recently discovered coronavirus causes coronavirus disease COVID-19.COVID-19 is the infectious disease caused by the most recently discovered coronavirus. This new virus and disease were unknown before the outbreak began in Wuhan, China, in December 2019.

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

## Data Augmentation
Data Augmentation encompasses a suite of techniques that enhance the size and quality of training datasets such that better Deep Learning models can be built using them. The image augmentation algorithms discussed in this survey include geometric transformations, color space augmentations, kernel filters, mixing images, random erasing, feature space augmentation
## Training
 Training is done on three different models
 -VGG-16
 -Resnet
 -Inception
## Transfer Learning
Transfer learning is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but 
related problem. We have applied transfer learning here on Inception model. 

## Results

We present the results in terms of both the per-class Area under ROC curve  graphs showing model accuracy and loss, as well as confusion matrix formed by treating the most confident class prediction as the final prediction. We obtain a mean AUROC of `0.9738` (2-class configuration).
Trained Weights of VGG: https://nustedupk0-my.sharepoint.com/:u:/g/personal/unadeem_ee38ceme_student_nust_edu_pk/EVwjHQfzUbBCoh_f4ShIpnIBkZJAdIIGTRcpfRuaEZjQ2w?e=QlaBeh
Trained Weights of Inception:
### Comparative Analysis
 Training & Validation Accuracy of Training Models
|  Accuracy | VGG | Inception | Resnet |
|:-----:|:------:|:---------:|:--------:|
| Train |  70 |   1 | 0.985 |
| Val   | 70 |    1|  0.958|

