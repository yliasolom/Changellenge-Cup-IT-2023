# **Changellenge >> Cup IT 2023**

Welcome to the repository for the Changellenge >> Cup IT 2023, a challenging competition that puts forward practical tasks for business and IT specialists. With a team of like-minded individuals, you will go through the journey from a brief to a final result, presenting your solution to experts from top companies and having the opportunity to receive a career offer in the end. At the championship, you will develop the best applied solution for IT industry leaders, covering all stages from data analysis to presenting the solution to the client. In the final, each participant has the chance to gain an advantage in selection or receive an invitation to open positions from leading employers. Even if you don't make it to the end, you will be awarded a participant diploma, which you can utilize in your resume.

**Changellenge >> Cup IT** is one of the most renowned IT competitions in Russia, with over 7000 participants over the past 5 years. Now it's your turn!

### DATA SCIENCE
If you enjoy working with datasets and building statistical models based on real data, the Data Science section is for you. In this section, you will have the opportunity to work with Big Data and help companies take their business to the next level. We recommend participating in this section if you have basic knowledge and technical tools for Data Science.

## Case Analysis
- Personalization of social networks is a global trend that helps users receive relevant and interesting information.
- News feed is a familiar "place" for any person in the 21st century.
- Modern methods of machine learning and data analysis allow obtaining relevant content for users. Comments are a way for users to evaluate post content, ask questions, or provide useful information.
- Often, comments do not have relevant "load," so there is a need to display them in a specific ordered manner.
- There are several solutions that satisfy the users' need for relevant content. Solution (Method Selection).
------------------------------------

## Solution (Training and Validation)
To solve the case, we decided to use TF-IDF.

**TF-IDF** (Term Frequency-Inverse Document Frequency) is a statistical measure used to evaluate the importance of a word in the context of a document that is part of a document collection or corpus.

- We used a simple linear regression model and TfidfVectorizer.
- We evaluated the results using Normalized Discounted Cumulative Gain (NDCG) as the metric.

## Analysis and Conclusions
- The obtained score demonstrates that the chosen strategy effectively handles the task of ranking comments by popularity.
- With more thorough feature engineering, selection of a more complex model, and tuning, higher results and scores can be achieved.
- One of the promising options to consider is the methods used in the development of recommender systems, such as UserKNN (User-Item) models and various matrix factorization techniques, which allow for obtaining relevant rankings.
