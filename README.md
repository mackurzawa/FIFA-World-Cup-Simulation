# FIFA-World-Cup-Simulation
Model Predicting who will be the winner of FIFA World Cup 2022 

In this notebook I implemented a model that predicts who will be the winner of the 2022 FIFA World Cup.

It includes:
* Calculating xG of a team by avering their score in the latest matches
* Adjusting the xG of a team according to the previous opponent's ranking
* Adjusting the xG of a team according with who they are playing in the next match
* Adding time decay (latest matches have heavier weights)
* Simulating matches based on the xG of two teams
* Implementing the whole structure of the tournament (group stage and knockout stage)

Model is fully modifiable, that means:
* <b>We can use that model in future tournaments - we only need to download the dataset with newest matches and ranking</b>
* We can predict the winner of one match - with or without draws
* We can change parameters like date from which matches are taken into account
* We can modify the amount of iterations

We can simulate the whole tournament:

![alt text](https://raw.githubusercontent.com/mackurzawa/FIFA-World-Cup-Simulation/main/Probabilities%20of%20winning%20-%20whole%20tournamentPNG.PNG)

Or just the knockout stage:

![alt text](https://raw.githubusercontent.com/mackurzawa/FIFA-World-Cup-Simulation/main/Probabilities%20of%20winning%20-%20knockout%20stage.PNG)

Or just one match:

![alt text](https://raw.githubusercontent.com/mackurzawa/FIFA-World-Cup-Simulation/main/Predicting%20who%20wins%20-%20Poland%20vs%20France.PNG)

In the notebooks everything is clearly explained. If you have any questions don't hesitate to ask.

Used datasets:
* Match Results - https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017
* Elo Rating - https://eloratings.net/
