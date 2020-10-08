The Titanic challenge on Kaggle is a competition in which the task is to predict the survival or the death of a given passenger based on a set of variables describing him such as his age, his sex, or his passenger class on the boat. I have been playing with the Titanic dataset for a while, and I have recently achieved an accuracy score of 0.8134 on the public leaderboard. As I'm writing this post, I am ranked among the top 9% of all Kagglers: More than 4540 teams are currently competing.

In a form of a jupyter notebook, my solution goes through the basic steps of a data science pipeline:

Exploratory data analysis with visualizations <br />
Data cleaning<br />
Feature engineering<br />
Modeling<br />
Modelfine-tuning<br />

Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.

The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.
