This folder contains all code for the sentiment analysis. 

Sentiment_Analysis: 
- For initial sentiment calculations and creating new sentiment csv files, start here. This will read in the wrangled data and output the same data with sentiment scores, saving them as new csv files. 
- Drops all reviews that do not include text. For analysis using all scores, including those without text, please use the "clean" csv files as opposed to the "sent_" csv files that this code outputs 
- This code performs no analysis of it's own per sae, in that it conducts sentiment analysis, but it does not contain any outputs for the presentation or final paper

Top_Ten_Sentiments:
- outputs the top 10 most positive and most negative reviews for all three apps using compound score and positive/negative scores 

RF_Score: 
- This RF model attempts to classify and predict user review scores by using sentiment scores and total character length of review. 
- It do the thing. 
- Also contains visualization outputs for the presentation
- Contains the combined super model to test amazon product reviews

LR_Score: 
- This Logistic regression model attempts to classify and predict user review scores by using sentiment scores and total character length of review. 
- It do the thing. 
- Also contains visualization outputs for the presentation

Super_Model:
- Contains the combined super model to test amazon product reviews
- Tests, optimizes, and visualizes the results 
