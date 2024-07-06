# Simple ML Email Spam Prediction Model

## Introduction
We can classify mails as two types

- Spam mail: Free entry in 2 a weekly comp to win FA Cup Final tkts 21st May 2005. Text FA to 87121 to receive entry question
- Ham mail: for instance, a mail that sent by family members, friends or co-workers.

We are going to try to look at mail and predict whether mails fall under category **``Spam mail``** or **``Ham mail``**

## Workflow
![Untitled (9)](https://github.com/wildanzzam/ML-Email-Spam-Prediction/assets/141975092/cfa07781-30b4-4035-a02d-411301f1731c)

- **Mail Data**

  First, we need to get the mail data for both spam mails as well as ham mail. We will use this data to train our Machine Learning Model

- **Data Pre-Processing**

  It is easier for Machine or Computer to understand numbers. Int term of text or long text like paragraph, computer might find it to be difficult to process. 
  We will try to convert the necessary text and paragraph into number which will be done in this workflow data processing.

- **A/B Testing**

  After processing and cleaning our data. We will split our dataset into training data and testing data. This training data will be utilized to feed machine learning model and train it. The test data will be
  used to evaluate the model later.

- **Logistic Regression Model**
  We will use Logistic Regression Model because this model is the suitable one when it comes to train binary classification model. Binary classification means there will be 2 classes that we will be classifying.   In this case it would be our spam mail and ham mail.

## Test Model
![Untitled (10)](https://github.com/wildanzzam/ML-Email-Spam-Prediction/assets/141975092/d5e3f75c-884d-4a65-bc8d-327f26bd3ba8)
