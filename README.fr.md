# Coveo Front End Challenge
## Le défi

À travers les années, il y a tellement de Pokemon qui ont été ajouté dans le Pokedex qu'il est maintenant nécessaire d'avoir une fonction de recherche avancée.
Ton défi, si tu l'acceptes, est de monter une interface de recherche de base basée sur l'API de recherche REST de Coveo.

Voir la [documentation de l'API de recherche REST](https://docs.coveo.com/en/13/).

Tu peux y accéder via https://platform.cloud.coveo.com/rest/search/v2 avec le token qui te sera fournit.
Ce token te donne accès à un index contenant les différents Pokemons qui existent dans la [Pokemon Database](pokemondb.net).

## Exemples
#### Pour chercher pour Pikachu

    https://platform.cloud.coveo.com/rest/search/v2?access_token=YOUR_TOKEN&q=pikachu

#### Pour chercher pour des pokemon de la génération 1

    https://platform.cloud.coveo.com/rest/search/v2?access_token=YOUR_TOKEN&q=@generation=1

#### Pour chercher pour des Pokemon de type *"Steel"*

    https://platform.cloud.coveo.com/rest/search/v2?access_token=YOUR_TOKEN&q=@type=="Steel"

## Plus d'informations

- [La documentation sur comment faire une recherche](https://docs.coveo.com/en/1445)
- [La documentation sur les paramètres de l'API](https://docs.coveo.com/en/13)
- [La documentation sur la syntaxe de query](https://docs.coveo.com/en/1552)
- [La documentation sur le format de la réponse](https://docs.coveo.com/en/1443)

## Inspiration
Si tu as besoin d'inspiration:

* https://connect.coveo.com/s/global-search/%40uri#q=Search%20API
* http://help.salesforce.com

Mais ne copie pas de code! On va le savoir :)

## Conseils

- **Tente de créer ta solution comme si c'était du vrai code de production**. Montre nous comment tu crées du code propre et maintenable qui fait des choses incroyables. Construit quelque chose à laquelle nous serions heureux de contribuer. Ceci n'est pas un concours de programmation où les "hack" malpropres remportent la victoire.
- N'hésite pas à ajouter des fonctionnalités! Nous sommes curieux de voir ce à quoi tu peux penser. Nous nous attendrons à la même chose si tu travailles avec nous.
- La documentation et la maintenabilité est un plus.
- N'oublie pas les tests unitaires.
