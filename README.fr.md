# Coveo Front End Challenge
## Le défi

Nous avons indexé les vins et bières disponibles sur le site de la SAQ et les avons rendus accessibles via notre REST Search API.
Ton défi, si tu l'acceptes, est de monter une interface de recherche de base basée sur l'API de recherche REST de Coveo.

Voir la [documentation de l'API de recherche REST](https://developers.coveo.com/display/SearchREST/Invoking+the+REST+Search+API).

Tu peux y accéder via https://cloudplatform.coveo.com/rest/search avec le token qui te sera fournit.
Ce token te donne accès à un index contenant les différents alcools en vente à la [SAQ](https://www.saq.com).

## Exemples
#### Pour chercher pour des bières rousses

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=Bi%C3%A8re%20rousse

#### Pour chercher pour des boissons à moins de 10$

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=@tpprixnum%3C10

#### Pour chercher pour des Merlot

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=@tpcepagenomsplitgroup==Merlot

## Plus d'informations

- [La documentation sur la syntaxe de requêtes](http://onlinehelp.coveo.com/en/ces/7.0/User/coveo_query_syntax_reference.htm)
- [La documentation sur l'API](https://developers.coveo.com/display/public/SearchREST/Invoking+the+REST+Search+API)
- [La documentation sur les paramètres](https://developers.coveo.com/display/SearchREST/Query+Parameters)
- [La documentation sur le format de la réponse](https://developers.coveo.com/display/SearchREST/Query+Results)

## Inspiration
Si tu as besoin d'inspiration:

* http://saq.coveodemo.com
* http://support.logitech.com
* http://help.salesforce.com

Mais ne copie pas de code! On va le savoir :)

## Obligatoire

- Le résultat final doit absolument être disponible publiquement sur l'internet. Heroku, AWS, Microsoft, Google Cloud, etc. ont tous des versions gratuites que vous pouvez utilisez. Si nous devons installer et configurer votre projet localement pour l'évaluer, vous serez pénalisé.

## Conseils

- **Tente de créer ta solution comme si c'était du vrai code de production**. Montre nous comment tu crées du code propre et maintenable qui fait des choses incroyables. Construit quelque chose à laquelle nous serions heureux de contribuer. Ceci n'est pas un concours de programmation où les "hack" malpropres remportent la victoire.
- N'hésite pas à ajouter des fonctionnalités! Nous sommes curieux de voir ce à quoi tu peux penser. Nous nous attendrons à la même chose si tu travailles avec nous.
- La documentation et la maintenabilité est un plus.
- N'oublie pas les tests unitaires.
- On ne cherche pas à savoir si vous pouvez uniquement suivre des instructions (sinon tous les résultats seraient pareils). On veut savoir qu'est-ce que **tu** contribues lorsque tu travailles sur un projet. C'est quoi ton secret. Plus de fonctionnalités? Meilleure solution? Idées originales?