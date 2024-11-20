# Project Name : Telecom Churn prediction (Kaggle Competition)

Case study to analyse a large dataset and use it for following tasks

- Identifying KPIs that can help telecom provider take better decisions.
- get the best possible prediction using various ML models.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.
- Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition. For many incumbent operators, retaining high profitable customers is the number one business goal.
- To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn. We will prepare various models to get best accuracy score and identify important KPIs.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We got best accuracy score and metrics from Random Forest model where we only used cleaned data without much preprocessing.We got accuracy of 94.19% and 94.32% for train set and test set respectively, also 94.39% accuracy in kaggle.
- Factors like average revenue per user, total incoming and out-going calls and recharge amount decreases on monthly basis for users who churned, telecom provider should analyse decrease in two- three of these factors and provide special offers/ better customer service to these kind of customers. This can help in mitigating customer to churn.
- Collectively from feature importance of predictive models we can say that Total incoming minutes of usage is most important feature in determining churn, and as per logistic regression it is inversely proportional to churn. This means if incoming minutes of usage for august are decreasing user are more like to get churned.
- telecom company should monitor id total incoming minutes of usage for customer is decreasing on monthly basis they should send them some special offers immediately and if possible ask a customer representative for asking their reviews and how their experience can be improved.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.13.2
- sklearn - version 1.2.2
- statsmodel - version 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@Tejas050798] - feel free to contact me!
