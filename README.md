# Smoker-Propensity-and-Smoker-Liar-Detection
Internship Project: Built a predictive classification model in Python to detect smoker propensity and liar detection using underwriting data

Disclaimer: For confidential reasons, the project here will only show generalized codes and contain no confidential information about the company and the final results.

### Project details
In this project, we have two different models: smoker propensity model and smoker liar detection model. The smoker propensity model can predict which applicant is more likely to be a smoker. Meanwhile, the smoker liar model can predict which applicant is more likely to be a smoker liar, which is an applicant who lies about their tobacco use. 

### Model characteristics
Two models share similar model characteristics. We use the same performance metrics on both, but each produces different statistical distribution and outcomes. Also, they follow the same procedure: 
1) Problem definition
2) Data acquisition
3) Modeling
4) Evaluation
5) Feature importances
6) Experiementation

### Problem definition
In life insurance, it is essentail to obtain accurate knowledge of an individual’s smoking status in assessing mortality risks as smoking increases the risk of cardiovascular diseases, cancers, and other illnesses. Relying solely on the self-reported smoking status poses a problem with insurance fraud as some applicants may be motivated to give false information about their tobacco use to get better insurance coverage. Therefore, in this project, we aim to build two models, one will detect the probability that an applicant is a smoker while the other one will find the probability that an applicant lies about their tobacco use. 

As we are moving towards a more data-driven automated process, these two models will serve as a safety net to reduce the risks a company will have to go through if applicants are motivated to give false information about their smoking status. These two models will prevent people from sneaking through the automated process.

This type of problem is a supervised machine learning project, which means we will be figuring out the patterns based on input-output pairs and then apply the pattern to other inputs to find outputs. In other words, the model will be learning patterns from previous cases or what it saw previously, historically and then use what it learns to analyze a new set of data to make predictions.
