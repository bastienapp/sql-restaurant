# Entraînement aux bases de données

## 1. Modélisation : 

Des restaurants ont un nom, une adresse.
Chaque restaurant possède un ou plusieurs menus, un menu n'appartenant qu'à un seul restaurant.
Un menu est composé d'un titre et d'un ou plusieurs plats.
Un plat est composé d'un nom et d'un prix et peut appartenir à un ou plusieurs menus.
Un restaurant possède un propriétaire : un propriétaire est spécifié par un nom, une adresse et un numero de siret.
Un propriétaire peut posséder plusieurs restaurant.

## 2. SQL

Importer la base de données à partir du fichier `restaurant.sql` et faire les requêtes suivantes :

1) le nom des restaurant par ordre alphabétique

2) le nom et prix des plats, par ordre de prix décroissant

3) les nom de restaurants qui sont à Paris

4) les villes et le nombre de restaurant associé à chaque ville

5) tous les noms de plats (sans doublon) qui appartiennent à au moins un menu 

6) pour chaque restaurant, son nom et le nombre de menus qu'il propose

7) les noms des restaurants dont au moins un menu est supérieur à 30€

8) les noms et nombre de plats des trois menus qui ont le plus de plats, par ordre décroissant de nombre de plats

9) le restaurant dont la moyenne des prix de tous ses plats est la plus élevée
