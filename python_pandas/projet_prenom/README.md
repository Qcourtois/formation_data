# Projet prénom

## Intro :
Objectif : Se familiariser avec la librairie Pandas en Python et la manipuler.
Date de réalisation : Fin mai 2026

### À noter :
Première utilisation de Pandas au sein de la formation, et comme on l'a beaucoup utilisée, j'ai eu une vraie montée en compétence depuis.
L'objectif étant d'utiliser les méthodes Pandas, les graphiques servent à visualiser rapidement des résultats, mais ne sont pas travaillés pour une belle visualisation.

**Utilisation de l'IA sur ce projet : 0 %**   J'ai pu réussir à tout faire grâce à la documentation Pandas officielle.

## Description
Étude de la répartition des prénoms en France depuis les années 1900.

### Dataset du projet

Ce projet s'insère encore une fois dans le cadre de l'Open Data. Cette fois ci nous analyserons conjointement deux datasets :

    Un fichier de données nationales qui contient les prénoms attribués aux enfants nés en France (hors Mayotte) entre 1900 et 2018 et les effectifs par sexe associés à chaque prénom. Les données sont classées par département. Le fichier contient 3.5 millions de lignes. Le fichier est disponible à cette adresse : https://www.data.gouv.fr/fr/datasets/ficher-des-prenoms-de-1900-a-2018/
    Un second dataset issu du travail de Mike Campbell au travers de son site web "Behind the Name" : https://www.behindthename.com/


### Contexte du projet

L'analyse des prénoms n'a rien de nouveau en soi, c'est même un grand classique : analyse de popularité instantanée, historique, "changement de sexe" des prénoms, etc. Voici deux exemples de liens ayant réutilisé ce 1er dataset :

    Réutilisation de type "analyse" (évolution dans le temps, …) : https://www.lefigaro.fr/fig-data/prenoms/ (désolé…)
    Réutilisation de type "podium" des prénoms — Insee : https://www.insee.fr/fr/statistiques/3532172

Vous pourrez très facilement retrouver nombre d'analyses en allant voir les "réutilisations" et "contributions communautaires" en bas de page sur data.gouv.fr par exemple.

Le réel apport que nous pouvons proposer dans ce projet est d'inclure une dimension supplémentaire à l'analyse : les langues d'origine des prénoms.
