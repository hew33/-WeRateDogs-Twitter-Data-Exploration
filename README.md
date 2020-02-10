# WeRateDogs-Twitter-Data-Exploration
Wrangling WeRateDogs Twitter data and creating trustworthy analyses and visualizations on dog ratings.
## Introduction
WeRateDogs is a Twitter account that rates people's dogs with humorous comments. These ratings almost always have a denominator of 10. WeRateDogs has over 4 million followers and has received international media coverage. This project was aimed to discover what makes the followers give high ratings to the dogs.
## Steps in the project
1. Gathering three datasets:
  * Manually downloaded the dataset of 2356 basic tweets data.
  * Programmatically downloaded the image prediction file using Request library.
  * Gathered additional data from Twitter's API.
2. Assessing and cleaning data:
  * Fixed the wrong data type
  * Corrected the wrong rating and dog stage data by extracting from the tweet text column.
  * Split tables, making each type of observational unit form only one table and solving the problem of too much missing values.
3. Storing, analyzing and visualizing the wrangled data.
## Questions to be answered:
1. What stage of a dog has higher ratings on average?
2. What breed of a dog gets higher ratings on average?
3. What is the relationship between dog ratings and their favorite counts and retweet counts?
## Key insights
Dogs at floofer stage have higher ratings on average, bouvier des flandres dogs have higher rating on average. Retweet counts and favorite count has strong and positive linear relationship, but retweet count & rating, favorite count & rating have relatively weak positive linear relationships.
By doing the hypothesis testing, I found that tweets with higher rating dogs are more likely to have more favorite counts and tweets with higher rating dogs are more likely to have more retweet counts.
