# ACE_592_Dating_Sim
Project Repo for ACE_592 Dating Sim Project

What is this?:
This Repo acts as a running log and version control for Isaac Wisthuff and Jack Hanley's ACE_592 Data Science Final Project. 

Running this Code: 
We recommend running the code in Jupyter notebook (note: you will have to download missing packages into your existing conda environment as needed). Simply download the files found in the Box link in the Wrangled_Data README documentation. When you open code in Jupyter notebook, simply change the dir_ line to match your working directory (this is always found in the second box on Jupyter notebook), and hit run. The code should take care of the rest : ) 

Project Overview: This project seeks to analyze reviews from the three most popular dating apps (Tinder, Hinge, and Bumble) between 2018-2022. This project uses Google Play Store review data for Tinder, Bumble, and Hinge from 2014-2022 and comes from Kaggle.com, an open-source data platform. The overarching goal of this project is to analyze how user sentiment and satisfaction changed pre, during, and post-pandemic, using Google Play reviews. More specifically, the goal of this project is to answer the following questions:   

- Were there any noticable trends in review data between 2018-2022? 
  - What is the distribution of review scores over the lifetimes of the apps, the apps pre, during, and post-pandemic, and purely post-pandemic?
  - How did the average review score change between 2018-2022? 
- Using sentiment analysis, how did review sentiment change over time between 2018-2022? 
  - Was there a noticeable drop during the pandemic, or a notable surge of positivity post-pandemic?
  - What are the common themes/words/complaints between the most negative sentiment reviews?
  - Is there a correlation between sentiment score and review score? 
  - Can sentiment be used to accurately predict a user's review score using a Random Forest or Multilinear Regression machine learning algorithm? 
  - How did overall review sentiment change over time? How did average sentiment over time compare to the average review score? 
- How prevelent are bots on dating apps and how frequently do users mention them in their reviews? 
  - Was there a noticable uptick in bot mentions during the pandemic? 
  - Are mentions of bots more common on certain dating apps relative to the total number of reviews for each app? (While reviews are not a perfect indicator of bot quantity on apps, they should serve as an acceptable proxy for the sake of drawing comparisons)
  - Can bot mention rate be correlated with other features of the data?
    - Is there a correlation between the bot mention rate and week-to-week average review score? 
    - Is there a correlation between the bot mention rate and week-to-week average review sentiment?
- What (if any) controversial topics come up frequently in reviews? Can they be corrolated with sentiment?
  - Mentions of race, racism, etc.
  - Mentions of political affiliation
  - Mentions of controversial topics like BLM, police, abortion, etc.
  - Mentions of gender or sexual orientation (e.g. transgender issues, how the app handles gender and sexual orientation)  

Directory Navigation: 

- Data_Wrangling: This folder contains all the code used to wrangle data
- Wrangled_Data: Aptly named, this folder contains all of the clean data for this project. Simply download this data, change the dir_ line to match your working directory (this is always found in the second box on Jupyter notebook), and hit run. The code should take care of the rest : ) 
- Trends: This folder contains the code used to do initial trend analysis of the data
  - Histograms over lifetime, 2018-2022, and post-pandemic
  - Rolling average review scores of each app over time between 2018-2022
- Sentiment_Analysis: This contains all code used to... 
  - Analyze_Sentiment: Perform preliminary data cleaning for sentiment analysis. Word count analysis. 
  - Top_Ten: Get the top 10 words across reviews using a variety of metrics 
  - RF_Score_Pred: Create and optimize Random Forest models to predict review scores 
  - MLR_Score_Pred: Create and optimize Multilinear regression models to predict review scores
  - Sentiment_Over_Time: Analyzes and compare the average rolling sentiment score with the average rolling review scores
- Bots: This folder contains all of the code for bot analysis


Data Sources: 
- Dating App Review Datasets:
  - https://www.kaggle.com/datasets/shivkumarganesh/tinder-google-play-store-review
  - https://www.kaggle.com/datasets/shivkumarganesh/hinge-google-play-store-review
  - https://www.kaggle.com/datasets/shivkumarganesh/bumble-dating-app-google-play-store-review
- Amazon Review Datasets: 
  - https://www.kaggle.com/datasets/yasserh/amazon-product-reviews-dataset
  - https://www.kaggle.com/datasets/akudnaver/amazon-reviews-dataset
  -  
