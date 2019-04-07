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
The calibration then allows to make predictions on other datasets. Here we made predictions on the samedataset used for learning.

3 differents methods : linear, polynomial, and Radial Basis function.

On the graph you can see that the best prediction is made with the RB function.

Find the right parameters for each method is important in the aim to have a precise prediction.

The big challenge is then to make accurate predictions on unknown datasets!


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
La calibration permet alors de faire des prédictions sur d'autres jeux de données. Ici nous avons réalisé des prédictions sur le même dataset utilisé pour l'apprentissage.
3 différentes méthodes ont été utilisées pour la prédiction : linéaire, polynomiale, et fonctoin radiale.

Sur le graphe vous pouvez voir que la meilleure prédiction est faite avec la fonctoin radiale.
Il est important de trouver les bons paramètres pour chaque méthode dans le but d'avoir un prédiction précise.
Le gros challenge est de faire des prédictions précises sur des jeux de données inconnus.


