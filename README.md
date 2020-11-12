# Machine-Learning-for-Complex-Pricing-Models
## UBS Quant Hackathon 2020 | Global Rank: Top 1/ 371

#### Problem: 
    Use a machine learning model to quote a structured product 
    
#### Data:
    15,000,000 samples with 164 features
    
#### Outcome:
    Ranked No. 1 out of 371 teams with MAE and MSE as 0.0269 and 0.000059 over test dataset on the global leaderboard
    
#### Project Details:
1. Performed data engineering with Python to process disorganized datasets and divide data into 350 batches for scaling purpose
2. Generated 432 features through feature transformation and group-by processing based on the distribution characteristics
3. Developed regression model (LightGBM) to predict target variable using DART tree type and MSE as objective function
4. Optimized model performance through hyper-parameters tuning and feature selection (123 features) based on importance

![avatar](D:\\Fordham\\UBS\\results\\202010212.png)
