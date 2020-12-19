# DM_Project
l'objectif du projet est de: 

• Maitriser l’API de twitter pour l’extraction des tweets.

• Maitriser la partie NLP (naturallanguageprocessing) avec NLTK en Python.

• Appliquer les principes de nettoyage des données.

• Classer les tweets: regrouper ensemble les tweets qui sont similaires.

# collecte des tweets

1- dans la première partie on a collecter les tweet à l'aide du bibliotheque *tweepy*, les tweet sont stockées dans des fichiers json.

> les tweets collectés doivent être netoyés
# Prétraitement des tweets
Le nettoyage des tweets comprendra plusieurs choses :

> - Enlever les emojis : pour cela il faut un module Python spécial (si vous connaissez des approches plus simples mettez-les en commentaire ça m’intéresse).
> - Retirer la ponctuation : très facile avec les reg-ex.
> - Retirer les caractères spéciaux : très facile avec les reg-ex mais tous les caractères ne seront pas retirés dans un premier temps. Les tweets sont des objets très sales !.
> - Retirer les chiffres : avec une Reg-ex aussi.
> - Changer les lettres majuscules en minuscules
