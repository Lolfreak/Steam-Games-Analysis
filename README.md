# Welcome to Steam-Games-Analysis!
## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Steam Games from the [Steam Games Dataset](https://www.kaggle.com/datasets/nikdavis/steam-store-games?resource=download) from [Kaggle](https://www.kaggle.com). The walkthrough is presented [here](https://github.com/Lolfreak/Steam-Games-Analysis), please view the source code in order from:
1. [Data Cleaning](https://github.com/Lolfreak/Steam-Games-Analysis/blob/main/data-cleaning.ipynb)
2. [Data Visualization](https://github.com/Lolfreak/Steam-Games-Analysis/blob/main/data_visualization.ipynb)
3. [Machine Learning](https://github.com/Lolfreak/Steam-Games-Analysis/blob/main/MachineLearning.ipynb)
4. [Presentation Slides](https://github.com/Lolfreak/Steam-Games-Analysis/blob/main/FCSD%20Group%206%20SC1015%20Steam%20Games%20Analysis.pdf) (Optional)
## List of Contributors (FCSD_TEAM 6)
* ![4b73dc1055a27d3a5b9e2a37be344b412](https://github.com/Lolfreak/Steam-Games-Analysis/assets/70129212/39188377-9def-4118-8238-e70b6158a0c1) Glyn Jong ([@Glynjong](https://github.com/Glynjong)) - Machine Learning (Core Analysis)
* ![ddoti21-a26e9393-d2ca-4802-a142-4cc3329d07da2](https://github.com/Lolfreak/Steam-Games-Analysis/assets/70129212/4fea2ff8-b4e1-4a2b-9caa-06eb523ad547) Brian Goh ([@ykrainn](https://github.com/ykrainn)) - Data Cleaning & Data Visualisation (Set the stage)
* ![Beru_Solo_leveling2](https://github.com/Lolfreak/Steam-Games-Analysis/assets/70129212/29320996-d64d-4374-b3c7-638bb9b15668) Muhd Alfiq ([@Lolfreak](https://github.com/Lolfreak)) - Data Analysis, Conclusion (Your motivation & Finish Strong)
## Background & Motivation
- In 2023, the Steam platform reported around 33 million peak concurrent Steam users worldwide, an increase from 27.4 million in just two years from 2021. There are also over 73 thousand games available on Steam, with over 9000 games being published in the first 9 months of 2023 alone. This shows that Steam is the main platform of many gamers who would want to purchase and play many different varieties of games.
- With a high number of active users on Steam, what can businesses and game companies do to leverage on this platform by learning about the trends in gaming. This leads to our problem definition.
## Problem Definition
- We would to like to **find out what makes a video game (on steam) popular**.
- Which model is used to be the best to predict it?
## Models Used
- [Random Forest Classifier](https://scikit-learn.org/stable/modules/ensemble.html#random-forests) - An ensemble learning method for classification and regression
- [XGBoost](https://machinelearningmastery.com/feature-importance-and-feature-selection-with-xgboost-in-python/) (eXtreme Gradient Boosting) - Distributed Gradient Boosted Decision Tree
- [AdaBoost](https://scikit-learn.org/stable/modules/ensemble.html#adaboost) (Adaptive Boosting) - A decision tree which uses a boost technique that makes use of a statistical classification meta-algorithm
- [HistGradientBoostingRegressor](https://scikit-learn.org/stable/modules/ensemble.html) (Histogram Gradient Boosting) - A boosting regressor which uses an ensemble machine learning algorithm.
## Conclusion
- We have found out that there are **5 main factors** that affects average playtime which makes games popular. These **5 factors** are **Owners, Workshop, Multiplayer, Trading Cards and Age**. We will omit Owners and Age as it is not a factor that can be used to work on new games.
- We were surprised with the results as we have gained insight on how gamers nowadays would like **multiplayer games** that have **trading cards** and have a **community workshop**. This shows that gamers would like to play games when they are able to play it with their friends or online players. Gamers would also value getting rewards when they play a game as trading cards are given to the player after a set number of hours which makes gamers feel rewarded. Also, the trading card itself can also be sold for real-life money. Finally, gamers also prefer to be able to mod or modify and change the game that adds to the replayability of the game which increases the average playtime of the game.
- Thus, we would recommend businesses and investors to work on new games that are able to satisfy these 3 factors which are, the game has to be a **multiplayer game**, the game has to provide or **have a community workshop** and also have **trading cards**. This will ensure that the new game will have **all the popular factors** which attracts gamers. Thus, this will exponentially increase the chance on **making the next popular game**. 
## Lessons Learned/Key Takeaways
- Normalize data with large value by using natural log.
- Do one-hot encoding by splitting the columns for ito be used for data analysis into individual variables.
- Handling large datasets and analyzing our given dataset and trying to find a suitable predictor.
- Identifying and retaining the important data while removing the irrelevant data. (Streamlining the data)
- Work with limited results and drawing suitable connections.
- Finding correlation between the response variable and the predictor variables.
- Learn how to use regex (Regular Expression) to allow us to remove certain words and phrases on a string.
- Learning many different forms of Machine Learning Models which were not taught in the SC1015 course such as Random Forest Classifier and XGBoost.
## References
- [Steam Games Dataset](https://www.kaggle.com/datasets/nikdavis/steam-store-games?resource=download)
- [Steam Spy](https://steamspy.com)
- [Steam Charts](https://steamdb.info/charts/)
- [Steam Background Sales](https://www.statista.com/topics/4282/steam/#topicOverview)
- [How brands can leverage gaming as an engagement channel](https://www.warc.com/newsandopinion/opinion/how-brands-can-leverage-gaming-as-an-engagement-channel/en-gb/3931)
- [What Do Investors Look for in a Game Developer?](https://www.gamedeveloper.com/business/what-do-investors-look-for-in-a-game-developer-)
# ![8a16xve5nzs81](https://github.com/Lolfreak/Steam-Games-Analysis/assets/70129212/2bda4f79-751f-4f6d-8644-9b569c2c0210)
