# ACE_592_Dating_Sim
Project Repo for ACE_592 Dating Sim Project

What is this?:
This Repo acts as a running log and version control for Isaac Wisthuff and Jack Hanley's ACE_592 Data Science Final Project. 

Project Overview: This project seeks to analyze reviews from the three most popular dating apps (Tindr, Hinge, and Bumble) between 2018-2022. The overarching goal of this project is to use the dating app reviews to determine how dating app use and user satisfaction changed pre, during, and post-pandemic. We will perform a numerical and text analysis of the data in order to answer the following questions:   

- Were their any noticable trends in review data between 2018-2022? 
  - What is the distribution of review scores over the lifetimes of the apps, the apps pre, during, and post-pandemic, and purely post-pandemic?
  - How did the average review score change between 2018-2022? 
- Using sentiment analysis, how did review sentiment change over time between 2018-2022? 
  - Was there a noticable change during the pandemic, or a notable surge of positivity post pandemic?
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

Directory Navigation: 

- Data_Wrangling: This folder contains all the code used to wrangle data
- Wrangled_Data: Aptly named, this folder contains all of the clean data for this project 
- Trends: This folder contains the code used to do initial trend analysis of the data
  - Histograms over lifetime, 2018-2022, and post-pandemic
  - Rolling average review scores of each app over time between 2018-2022
- Sentiment_Analysis: This contains all code used to... 
  - Analyze sentiment and clean data for sentiment analysis
  - Get the top 10 words across reviews using a variety of metrics 
  - Create and optimize Random Forest and Multilinear regression models used to predict review scores 
  - Sentiment_Over_Time analyzes and compares the average rolling sentiment score with the average rolling review score
- Bots: This folder contains all of the code for bot analysis
