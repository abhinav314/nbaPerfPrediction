# NBA Performance Prediction and Roster Generation

This project is for MGMT 586 - Introduction to Python at Krannert School of Management, developed by Abhinav Chanda, Samir Husain, Sachin Arakeri, Shivendra Kuman and Lingtong Guo.

Project descriptionBusiness Context:
- Develop a framework to help NBA teams predict player performance for upcoming seasons, based on their on-court efficiency
- Identify the most "efficient" players position-wise
- Recommend player trades and generate a sample roster based on a stipulated budget for the upcoming season
- We chose to implement the solution for Indiana Pacers, within a budget of $50 Mn

Implementation:
- Using ESPN's NBA data for the past decade, we developed a boosting algorithm to predict a basketball player's Player Efficiency Rating (PER - http://insider.espn.com/nba/hollinger/statistics/_/order/false). We achieved 98% prediction accuracy
- We identified the top 5 players for the Indiana Pacers based on our PER predictions
- Taking note of the positions of these players, we developed a Python based algorithm to generate player trades optimizing the "bang-for-buck" factor
- The solution is scalable and runs in less than a minute. It can be extended to any sport and will require model re-training and the budget cap as an input
