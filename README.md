## Predicting Wireless Service Purchases: A Neural Network Classification Case
East-West Airlines launched a direct mailing campaign in partnership with wireless provider **Telcon**, aiming to sell wireless service contracts to airline customers. The campaign's goal is to **predict which customers are likely to purchase** based on their profile and past behavior, enabling targeted marketing and improved ROI.

### Objective
Build a **neural network classification model** using R to predict whether a customer will purchase a wireless phone plan (```Phone_Sale = 1``` ) based on customer profile data.

### Dataset
Source: Provided by course
File: EastWestAirlinesNN.csv
Target Variable:
```Phone_Sale``` : 1 = Purchased, 0 = Did not purchase
Predictor Variables:

Includes total miles flown, flight frequency, credit balance, number of years with airline, age, and more.

### Methodology
#### 1. Data Preprocessing

- Normalize all numerical predictors to (0,1)

- Train-test split using caret

- Visual inspection of variable distributions

#### 2. Modeling

- Train a single-hidden-layer neural network (neuralnet and nnet)

- Try different numbers of hidden units

- Compare with logistic regression as a baseline

#### 3. Evaluation

- Use confusion matrix and accuracy to evaluate performance

- Visualize neural network structure
