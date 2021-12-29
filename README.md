# Udemy-Revenue-Optimization
Exploratory analysis of Udemy course and ML modeling of course pricing to optimize revenue

Udemy is one of the biggest massive online open course (MOOC) platforms. We obtained data from Kaggle that will provide information regarding the type of courses offered and how popular they are. 

We started by performing Exploratory Data Analysis (EDA) to investigate different variables present in the dataset and their statistical properties. We then developed a machine learning model to determine the optimal pricing for revenue maximization.

There are two steps to our algorithm:
1.	Predict a price range based on the courses' intrinsic parameters, and
2.	Predict the revenue based on the prices in the price range found in step 1.

We could not build a satisfactory model for step 1 based on existing data. Therefore, we adjusted our approach and used a list of prepopulated price ranges to feed into step 2. 
For step 2, the model has a R2 score of 0.28 and RMSE of 1.9. The model's behavior matches the theoretical prediction, where ascending price leads to descending subscribers, but the overall revenue still increases because the increasing price makes up for the revenue loss from losing subscriber.

Based on the model, we can suggest to instructors to always price their courses highly to maximize revenue. However, we know that profitability is not the only goal of Udemy. As one of the biggest MOOCs, Udemy's mission is to improve lives through affordable, and raising all course prices to the 200-dollar range would greatly reduce the accessibility of the courses and does not align with their mission.
