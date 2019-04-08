-----------------------------------------------------------------
			ENGLISH
-----------------------------------------------------------------

This python3 programm use the following ia libraries :
numpy
sklearn
csv
matplotlib

It makes a learning from a dataset containing the date and the price of the stock price of a company during a given time.
You can get datasets at https://finance.yahoo.com/quote/AAPL/history?period1=1546815600&period2=1554588000&interval=1d&filter=history&frequency=1d

Here the dataset is the stock price of APPLE during march 2019.

The programm learn prices and dates in a csv file thanks to sklearn.
It internally calibrate a neuronal network.
The calibration then allows to make predictions on other datasets. Here we made predictions on the day 29 of the month

3 differents methods : linear, polynomial, and Radial Basis function.

On the graph you can see that the function that fit the best the given points is the RB function, so it is with this function that we are going to be able to de the most accurate predictions.

Finding the right parameters for each method is important in the aim to fit the closest as possible the input points.


-----------------------------------------------------------------
			FRANCAIS
-----------------------------------------------------------------

Ce programme python3 utilise les librairies suivantes :
numpy
sklearn
csv
matplotlib
Il effectue un apprentissage grâce à un jeu de données contenant la date et le prix du "stockprice" d'un companie durant une période de temps donnée.
Vous pouvez récupérer le dataset à l'adresse suivante : https://finance.yahoo.com/quote/AAPL/history?period1=1546815600&period2=1554588000&interval=1d&filter=history&frequency=1d
Ici le jeu de données est le stockprice d'APPLE durant le mois de mars 2019.

Le programme apprend les prix et les dates dans un fichier csv grâce à sklearn.
Cela a pour effet de calibrer en interne un réseau de neurone.
La calibration permet alors de faire des prédictions sur d'autres jeux de données. Ici nous avons réalisé une prédiction sur le jour 29 du mois de mars.
3 différentes méthodes ont été utilisées pour la prédiction : linéaire, polynomiale, et fonction radiale.

Sur le graphe vous pouvez voir que la fonction qui permet d'approcher les points d'entrée est la fonction radiale. C'est donc avec cette fonction que l'on doit pouvoir faire les meilleures prédictions.
Il est important de trouver les bons paramètres pour chaque méthode dans le but d'avoir un prédiction précise.


