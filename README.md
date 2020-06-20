# Proto Seguro Safe Driver Prediction
### Pujan Malavia 

![ps_logo](https://user-images.githubusercontent.com/19572673/62312158-79cccf80-b45b-11e9-8fe5-260ec1e52997.jpg)

## Abstract:
Nothing ruins the thrill of buying a brand new car more quickly than seeing your new insurance bill. The sting’s even more painful when you know you’re a good driver. It doesn’t seem fair that you have to pay so much if you’ve been cautious on the road for years.
Porto Seguro, one of Brazil’s largest auto and homeowner insurance companies, completely agrees. Inaccuracies in car insurance company’s claim predictions raise the cost of insurance for good drivers and reduce the price for bad ones.
In this competition, you’re challenged to build a model that predicts the probability that a driver will initiate an auto insurance claim in the next year. While Porto Seguro has used machine learning for the past 20 years, they’re looking to Kaggle’s machine learning community to explore new, more powerful methods. A more accurate prediction will allow them to further tailor their prices, and hopefully make auto insurance coverage more accessible to more drivers. 

https://www.kaggle.com/c/porto-seguro-safe-driver-prediction

https://www.portoseguro.com.br/

### Industry:
Insurance 

### Company Information:
Porto Seguro is the third largest Brazilian insurance company in Brazil, was founded in 1945 and has more than 13,000 employees. The company operates through its subsidiaries in Brazil and in Uruguay. It is headquartered in São Paulo.

The company offers car insurance, residential, health, life, business, consortium also offers auto and homeowners, pension, savings bonds and other financial services. Porto Seguro competes with Bradesco Seguros, BB Seguridade, SulAmérica, Mapfre, Zurich Insurance Group and others insurance and reinsurance companies in Brazil.

Porto Seguro is the leader on the auto and homeowner insurance segments in Brazil and has around 10 million clients all over the different business lines.

Currently the company its owned by the Brazilian billionaire Jayme Garfinkel and the bank Itaú Unibanco, through PSIUPAR (Porto Seguro Itaú Unibanco Participações S.A.). "Since establishing an alliance with the bank Itaú in August 2009, Porto Seguro products have been available at the bank’s branches." 

https://en.wikipedia.org/wiki/Porto_Seguro_S.A.

### Use Case:
Predict if a driver will file an insurance claim next year.

### Initial Dataset(s):
train.csv contains the training data, where each row corresponds to a policy holder, and the target columns signifies that a claim was filed.
test.csv contains the test data.
sample_submission.csv is submission file showing the correct format.

### Tool:
Python

### Data:
In this competition, you will predict the probability that an auto insurance policy holder files a claim.

In the train and test data, features that belong to similar groupings are tagged as such in the feature names (e.g., ind, reg, car, calc). In addition, feature names include the postfix bin to indicate binary features and cat to indicate categorical features. Features without these designations are either continuous or ordinal. Values of -1 indicate that the feature was missing from the observation. The target columns signifies whether or not a claim was filed for that policy holder.

### Data Fields:

id

target

ps_ind_01

ps_ind_02_cat

ps_ind_03

ps_ind_04_cat

ps_ind_05_cat

ps_ind_06_bin

ps_ind_07_bin

ps_ind_08_bin

ps_ind_09_bin

ps_ind_10_bin

ps_ind_11_bin

ps_ind_12_bin

ps_ind_13_bin

ps_ind_14

ps_ind_15

ps_ind_16_bin

ps_ind_17_bin

ps_ind_18_bin

ps_reg_01 - ps_reg_03

ps_car_01_cat - ps_car_11_cat

ps_car_11 - ps_car_15

ps_calc_01 - ps_calc_14

ps_calc_15_bin - ps_calc_20_bin
