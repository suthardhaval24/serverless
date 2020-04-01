# serverless

## Student Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
| Dhaval Suthar | 001475572 | suthar.d@husky.neu.edu |

## Description

Lambda project is a maven project which contains lambda Function whose responsibility to send an email to subscribe user about all the due bills. 


## CircleCI
1. build_deploy job:
  * Install AWS CLI and set profile 
  * Creates zip artifact of the project 
  * Uploads it to AWS S3 Bucket created for codeDeploy