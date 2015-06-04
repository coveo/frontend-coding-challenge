# Coveo JavaScript Challenge
## Le défi
Ton défi, si tu l'acceptes, est de monter une interface de recherche de base basée sur l'API de recherche REST de Coveo.

Voir la [documentation de l'API de recherche REST](https://developers.coveo.com/display/SearchREST/Invoking+the+REST+Search+API).

Tu peux y accéder via https://cloudplatform.coveo.com/rest/search avec le token qui te sera fournit.
Ce token te donne accès à un index contenant les différents alcools en vente à la [SAQ](saq.com).

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
- [La documentation sur le format de la réponse](https://developers.coveo.com/display/SearchREST/Query+Results).

## Inspiration
Si tu as besoin d'un exemple ou d'inspiration, tu peux regarder certains de nos sites:

* http://saq.coveodemo.com
* http://support.logitech.com
* http://help.salesforce.com

Mais ne copie pas de code! On va le savoir :)
