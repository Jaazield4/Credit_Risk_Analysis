# Credit_Risk_Analysis

## Overview
The purpose of the project was to use different methods in supervised machine learning, random oversampling, smote oversampling, undersampling, smoteenn, balanced random forrest classifier, and easy ensemble classifier to determine loan status. The reason for the use of so many methods was to find the one that was the most accurate and give the best results.

## Results

#### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/85451089/137673112-546729e1-5d15-4b53-8d72-1fcb0caa70dc.png)
![image](https://user-images.githubusercontent.com/85451089/137673148-e9e8d082-067f-459c-a22a-98fdb10f6f72.png)

- Using the naive random oversampling gave an accuracy score of about 0.65. While not bad it could be better
- The precision for high_risk was 100% while the precision for low_risk was 0.01
- Recall for high_risk was considerably higher than the low_risk as it was 0.73 and low_risk was 0.57

#### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/85451089/137673473-0a405849-c989-4643-ac35-116492d6bd3e.png)
![image](https://user-images.githubusercontent.com/85451089/137673510-67103337-0ce3-43e5-8ab0-40bd28657f50.png)

- By using Smote oversampling the accuracy score had a minor change to about 0.66
- The precision stayed the same as the naive random method with high_risk at 1.0 and low_risk at 0.01
- SMOTE brought the high and low risk recall's much closer as high_risk recall was 0.63 and low_risk 0.68

#### Undersampling
![image](https://user-images.githubusercontent.com/85451089/137673875-baa09780-59f9-4435-8bcd-a4b2ba7eca3f.png)
![image](https://user-images.githubusercontent.com/85451089/137673897-14a5a81e-3b53-4448-a69e-04e43719d81b.png)

- Using undersampling brought the accuracy score much lower to 0.54
- There was no change to presions with high_risk at 1.0 and low_risk at 0.01
- High_risk recall was .29 higher with 0.69 and low_risk performing poorly at 0.40

#### Smoteenn
![image](https://user-images.githubusercontent.com/85451089/137674074-c8fbc589-2b50-4252-b9ae-86d42f5dc85f.png)
![image](https://user-images.githubusercontent.com/85451089/137674109-a7a54109-4ae1-4ac8-99f2-52ede2303be3.png)

- Accuracy score was very similar to oversampling at 0.65
- Precision is the same at high_risk 1.0 and low_risk 0.01
- Recall was quite higher for the high_risk at 0.72 while low_risk had a recall score of 0.57

#### Balanced Random Forrest
![image](https://user-images.githubusercontent.com/85451089/137674314-8fb63bd2-ffa3-4937-85e7-e2d74cd9ee9c.png)
![image](https://user-images.githubusercontent.com/85451089/137674342-8982102e-9d57-4724-8b6f-5523382508da.png)

- Accuracy score went up quite a bit from the previous methods with it being 0.79
- Precision for high_risk went up to 0.03 and low_risk stayed the same at 1.0
- Recall scores were for high_risk 0.70 and low risk was 0.87

#### Easy Ensemble
![image](https://user-images.githubusercontent.com/85451089/137674557-8245ea65-9b9d-4867-92ed-9a4895ed8c30.png)
![image](https://user-images.githubusercontent.com/85451089/137674585-5c7e559c-14d3-467e-bd97-68c556749330.png)

- The easy ensemble method had the highest accuracy score by far with 0.93
- It also had the highest low_risk precision score with 0.09 and low risk stayed at 1.0
- Both recalls were very high as well with high_risk being 0.92 and low risk being 0.94


## Summary
To get the best results we can use the easy ensemble method as it provided the highest not only accuracy score but recall and precision scores. This will allow us to be as accurate as possible.

