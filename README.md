### Random-Forest-Classifier-Hyperparameters-Travel.com 

## Travel.com Data 

"Trips & Travel.Com" company wants to enable and establish a viable business model to expand its customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, the company is offering 5 types of packages - Basic, Standard, Deluxe, Super Deluxe, and King. Looking at the last year's data, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient. 

## Dataset

The dataset used for this project contains the following variables:

Travel.csv dataset (4888)

https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction

- `CustomerID`: Unique customer ID 
- `ProdTaken`: Taken product: 1/0 (Target) 
- `Age`: The age of the customer 
- `TypeofContact`: How the customer was contacted (Company invited or Self Inquiry)
- `CityTier`: City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. 
- `DurationOfPitch`: Duration of the pitch by a salesperson to the customer. (minute)
- `Occupation`: Occupation of the customer. 
- `Gender`: Gender of the customer. 
- `NumberOfPersonVisiting`: Total number of persons planning to take the trip with the customer. 
- `NumberOfFollowups`: Total number of follow-ups has been done by the salesperson after the sales pitch. 
- `ProductPitched`: Product pitched by the salesperson. 
- `PreferredPropertyStar`: Preferred hotel property rating by customer. 
- `MaritalStatus`: Marital status of the customer.
- `NumberOfTrips`: Average number of trips in a year by customer. 
- `Passport`: The customer has a passport or not (0: No, 1: Yes). 
- `PitchSatisfactionScore`: Sales pitch satisfaction score. 
- `OwnCar`: Whether the customers own a car or not (0: No, 1: Yes). 
- `NumberOfChildrenVisiting`: Total number of children age less than 5 planning to take the trip with the customer. 
- `Designation`: Designation of the customer in the current organization. 
- `MonthlyIncome`: Gross monthly income of the customer. 

## Model Building

The Random Forest model employed in this project utilizes random split hyperparameters, which create an ensemble of decision trees trained on diverse subsets of the training data. 

Evaluation of the model's performance is done using key metrics such as AUC-ROC, a widely-used measure that assesses the classifier's ability to distinguish between classes. The confusion matrix provides a comprehensive breakdown of the model's predictions, enabling a detailed analysis of true positives, true negatives, false positives, and false negatives. Classification reports offer a concise summary of precision, recall, F1 score, and support for each class. Additionally, the model provides insights into feature importance, facilitating feature selection, and understanding of the factors driving predictions. For further analysis, a single decision tree can be visualized to comprehend the underlying decision-making process.


