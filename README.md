# Tweets Clustering in python
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GhazwaMa/DM_Project/main?filepath=projet_DM.ipynb)

# Introduction :

Twitter est un réseau social dit de « microblogging » qui permet de communiquer sous la forme de messages courts ne dépassant pas 140 caractères appelés « tweets ». Ils peuvent contenir des URL sous forme raccourcie, des images, des émoticônes, des gifs animés et des vidéos.

# objectif :

l'objectif du projet est de: 

• Maitriser l’API de twitter pour l’extraction des tweets.

• Maitriser la partie NLP (naturallanguageprocessing) avec NLTK en Python.

• Appliquer les principes de nettoyage des données.

• Classer les tweets: regrouper ensemble les tweets qui sont similaires.

# collecte des tweets

1- dans la première partie on a collecter les tweet à l'aide du bibliotheque *tweepy*, les tweet sont stockées dans des fichiers json.

*les tweets collectés doivent être netoyés*

# Prétraitement des tweets
Le nettoyage des tweets comprendra plusieurs choses :

> - Enlever les emojis : pour cela il faut un module Python spécial (si vous connaissez des approches plus simples mettez-les en commentaire ça m’intéresse).
> - Retirer la ponctuation : très facile avec les reg-ex.
> - Retirer les caractères spéciaux : très facile avec les reg-ex mais tous les caractères ne seront pas retirés dans un premier temps. Les tweets sont des objets très sales !.
> - Retirer les chiffres : avec une Reg-ex aussi.
> - Changer les lettres majuscules en minuscules


# Clustering

> - extracting key words
> - Finding Optimal Clusters ( k=23 )
> - Plotting Clusters
> - printing tweets per cluster
