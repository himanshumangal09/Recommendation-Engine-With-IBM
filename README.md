# Recommendations Engines with IBM
This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.

##  Installations
This project requires Python 3.x and the following Python libraries installed:
- [Nltk](https://www.nltk.org/)
- [Pandas](http://pandas.pydata.org)
- [Progressbar](https://pypi.org/project/progressbar/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Summary:
The project aims to develop a recommendation system for articles on IBM's platform. It involves several tasks, which are as follows:

Exploratory Data Analysis (EDA):

This task is for data exploration to understand the data and its features.
Techniques such as data visualization, summary statistics, and data cleaning are used to prepare the data for further analysis.
Rank-Based Recommendations:

This task involves finding the most popular articles based on the most interactions (e.g., number of views, likes, etc.).
These popular articles are recommended to new users or anyone based on their preferences and interests.
User-User Based Collaborative Filtering:

In this task, users that have similar preferences and interests are identified based on the items they have interacted with.
The items interacted with by similar users are then recommended to the target user.
Content-Based Recommendations:

This task involves using Natural Language Processing (NLP) techniques to develop a content-based recommendation system.
The system recommends articles that are similar in terms of content and topics to the articles the user has interacted with.
Matrix Factorization:

The final task involves building a machine learning approach to building recommendations.
A matrix decomposition technique is used to analyze user-item interactions and predict new articles that the user might interact with in the future.
In summary, the project aims to develop a recommendation system for articles on IBM's platform using various techniques such as exploratory data analysis, rank-based recommendations, user-user based collaborative filtering, content-based recommendations, and matrix factorization.





## Data
- user-item-interactions.csv: file contains user interaction.
- articles_community.csv: file contains articles description.  

## Acknowledgments
I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [IBM](https://dataplatform.cloud.ibm.com/) for providing the data.
