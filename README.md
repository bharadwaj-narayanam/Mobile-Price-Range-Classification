# Mobile-Price-Range-Classification
Classifying mobiles into different price ranges depending on various factors.

## File
: Has all the code and analysis I have done for the classification
## Link to the dataset
Mobile Price range data: https://drive.google.com/file/d/1RuhUy4NQcRJBfaCh-sgW9c4g15cD71TT/view?usp=sharing

## About the Project
Understanding business problems plays an important role in data science. Price is the most effective attribute of marketing and business. It is the most important factor that decides the sales of that product. Mobile technology is a technology where users go, this technology also goes. The mobile phone is stimulating one of the most important technological revolutions in human history. This statement is not hyperbole. There are more mobile phones in use today than there are people. This portable technology consists of two-way communication, computing and networking technology. The number of mobile users in the world in 2019 is about 3.2 billion and increasingly in 2020 is about 3.5 billion. Different commercial activities, university courses, entertainment, communications are also done by a phone. Different organizational tasks, meetings also maintained and held virtually in this pandemic situation. As well as the use of mobile phones is increasing day by day and the prices also vary by their different attributes. Nowadays, mobile phones are selling in a huge number and within a short timespan new versions with new features are launched to market. There are many features which are important to consider a mobile price like brand, display, resolution, ram, camera, processor, chipset etc. So, it becomes very important for a company to decide on which features it should focus upon to maximize the sales of that particular mobile phone in the market. 

## Problem statement 
- The current project aims to figure out which of the attributes are the most important ones in predicting the price of the mobile phone in the market based on the data provided. - The dataset contained a list of columns or features including total energy a battery can store in one time measured in mAh, presence of bluetooth or not, speed at which microprocessor executes instructions,has dual sim support or not, front Camera megapixels etc. 
- The model was trained and validated using supervised ML models such as Linear regression, random forest, XG boost and KNN.

## Project description
### About the data
- The data consists of multiple features which contain information regarding several mobiles, and the price bracket they fall into.
- The data is balanced with 500 records for each of the mobile ranges.

### Steps
- Developed a multi-class classification model using algorithms such as Random forest, Decision trees, XGBoost and KNN to predict the price range of a mobile.
- This analysis was done on several important variables such as Internal memory, RAM etc. Multicollinearity was taken care of, using Variance Inflation Factor.
- Feature importance was calculated for all models, so as to find all variables with high impact on the price.
- Achieved an accuracy of 94.33% for test set in KNN and it turned out to be the best model for our data.

## Summary 
- Battery power, clock_speed, dual_sim, m_dep, mobile_wt, px_height, px_width, ram, sc_h, talk_time got linear relationship with our dependent variable price range.
- Ram has the highest impact on the price of the mobile.
- Using decision tree, we got a decent performance after tuning the hyperparameters. We found that there's some overfitting which is a usual problem with DT. 
- After DT, we have tried different bagging and boosting models which performed well as compared to the above models.
- XG boost model overfits here, so we could say that KNN is the best algorithm for the dataset.  
