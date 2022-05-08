# Credit_Risk_Analysis
## Challenge 17

# Porpouse 
Apply machine learning to solve credit card risk.Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.

#Resampling Models to Predict Credit Risk

LoanStats_2019Q1 information

![image](https://user-images.githubusercontent.com/96089967/167300322-195cbe6f-0468-421c-8deb-3f5796690d01.png)

Processed database
![image](https://user-images.githubusercontent.com/96089967/167300404-0e7a7634-8439-4354-9a13-c0bf9e700aaa.png)

low_risk     68470
high_risk      347

Naive Random Oversampling

Balanced accuracy score
0.6249984891886339

imbalanced classification report

![image](https://user-images.githubusercontent.com/96089967/167300639-c9d11ea8-743d-459b-b2ef-d6967938f8e4.png)


# SMOTEENN Algorithm to Predict Credit Risk

Balanced accuracy score
0.6249984891886339

Confusion matrix
![image](https://user-images.githubusercontent.com/96089967/167300727-eacd6fce-4660-4beb-a84b-a8c3cf01b949.png)

Imbalanced classification report
![image](https://user-images.githubusercontent.com/96089967/167300835-64f4ee26-e3ee-4524-bd55-69cdcac3034f.png)

Resample the data using the ClusterCentroids resampler
![image](https://user-images.githubusercontent.com/96089967/167300910-0287950c-ae27-43de-aabb-66fe4ba79561.png)


Balanced accuracy score
0.6249984891886339

Imbalanced classification report

![image](https://user-images.githubusercontent.com/96089967/167301015-154d9026-2161-4f35-b1f4-993d1c6aa77f.png)


Combination (Over and Under) Sampling

Balanced accuracy score
0.6400726134353378

Confusion matrix

![image](https://user-images.githubusercontent.com/96089967/167301103-c8a4d134-654f-43ff-a542-6206f79f64d9.png)

Imbalanced classification report

![image](https://user-images.githubusercontent.com/96089967/167301130-7fa68682-d053-4156-9d20-0a6fabbba3a7.png)

Processed database
![image](https://user-images.githubusercontent.com/96089967/167301240-28d97082-b590-4e34-a78e-4a721addafed.png)

Balanced Random Forest Classifier

Balanced accuracy score
0.67209249388625

Confusion matrix

![image](https://user-images.githubusercontent.com/96089967/167301327-53bd803a-e914-47f0-a0fb-fba61317450e.png)

Imbalanced classification report

![image](https://user-images.githubusercontent.com/96089967/167301360-eb0ee6bb-308a-4aa8-a232-90df439ada3a.png)

Easy Ensemble AdaBoost Classifier

Balanced accuracy score
0.925427358175101

Confusion matrix

![image](https://user-images.githubusercontent.com/96089967/167301439-6fa7154b-ec4f-4d58-bfa9-a95d941d9a82.png)


Imbalanced classification report
![image](https://user-images.githubusercontent.com/96089967/167301469-7cd41f5f-ab9a-4417-a21c-3fcd43d12b28.png)






# Ensemble Classifiers to Predict Credit Risk
