# Board-Game-Review-Prediction
Predict the game reviews 
This dataset is scrapped from web.
The size of the data set is: 81.3k x 20
Goal of the Problem: To predict the average rating using the described feature set.

This dataset consists of the following columns:

1. id
2. type
3. name
4. yearpublished
5. minplayers
6. maxplayers
7. playingtime
8. minplaytime
9. maxplaytime
10. minage
11. users_rated
12. average_rating
13. bayes_average_rating
14. total_owners
15. total_traders
16. total_wanters
17. total_wishers
18. total_comments
19. total_weights
20. average_weight

Algorithms used:
1. Linear Regression
2. Random Forest Regressor

Performance metric:
* Mean Squared Error

Conclusion:
Linear regression model gives us mse of about 2.08 while rando forest regressor gives 1.48. So for now Random forest is doing well.
