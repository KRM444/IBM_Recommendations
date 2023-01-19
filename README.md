# Recommendations with IBM


### Introduction:
In this project I analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles that they may like.

### File Descriptions:
- Recommendations_with_IBM.ipynb: Jupyter notebook containing main implementation and analysis.
- Recommendations_with_IBM.html: A copy of Recommendations_with_IBM.ipynb in html format.
- data/articles_community.csv: file with indexed items.
- data/user-item-interactions.csv: file with user-item interactions.


### Project
The project is divided into the following parts:

1) Exploratory Data Analysis 
   - Visualize the distribution of User Article Interaction

2) Rank Based Recommendations:
   - Obtain the top n articles in descending order 

3) User-User Based Collaborative Filtering:
   - Reformat the data to be shaped with users as the rows and articles as the columns
   - Provide an ordered list of the most similar users to that user (from most similar to least similar)
   - Use above users to find articles that can recommended

4) Matrix Factorization:
   - make article recommendations to the users on the IBM Watson Studio platform.
