# BoomBikes Sharing - Linear Regression Assignment
### Problem Statement: 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes
- How well those variables describe the bike demands

### Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Steps used for Model Building:
* Reading and Understanding the Data
* Visualising the Data
* Data Preparation
* Splitting the Data into Training and Testing Sets
* Rescaling the Features
* Building a linear model
* Residual Analysis of the train data
* Making Predictions Using the Final Model
* Model Evaluation

<!-- You can include any other section that is pertinent to your problem -->
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions:
The summary of the model after data interpretation, visualisation, data-preparation, model building and training, residual analysis and evaluation of test model are as follows-

- The R-squared value of the train set is 82.1% whereas the test set has a value of 80.88% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
- Our developed model's mean squared error is close to 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set.
- The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.
- We can conclude that the bike demands for the BoomBikes is company is dependent on the temperature and whether it is a workingday or not.
- Additionally more rentals seem to be demanded on the winters as compared to the summer and spring.
- We had observed that the months of September and October had higher use of rentals.
- In terms of days the maximum focus was on days like Wed, Thurs and Sat and more on holidays.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Recommendations:

- These interpretations help us derive meaningful insights in the bike rental market and the behaviour of the people.
- One of the recommendations based on this model are that there should be aggressive marketing in the summer and spring season to drive up rentals.
- Since the summer months also show low rental levels, a strong marketing strategy for the first 6 months of the year can assist in driving up the rental numbers.
- There has to be an approach required to introduce more users on days where the weather is less clear, perhaps with incentives or strategic deals.
- Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed to this idea and there has to a strong analysis done to retain the repeat customers.

## Contact
Created by @AjitShinde-Github - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
