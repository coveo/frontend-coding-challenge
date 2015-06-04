# Coveo JavaScript Challenge
## The challenge

The challenge, if you accept it, is about building a search interface based on Coveo REST API.

See [the documentation section](#documentation)

You can access this api through https://cloudplatform.coveo.com/rest/search with the token we will give you, or if you are courageous you can find it on your own. This token grants you acces to a Coveo index containing different types of alcools which are sold in [SAQ](saq.com).

## Exemples
#### Searching Amber Ales

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=Bi%C3%A8re%20rousse

#### Searching beers under 10$

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=@tpprixnum%3C10

#### Searching Merlot

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=@tpcepagenomsplitgroup==Merlot

## Documentation

- [Query syntax doc. syntax](http://onlinehelp.coveo.com/en/ces/7.0/User/coveo_query_syntax_reference.htm)
- [REST API doc.](https://developers.coveo.com/display/SearchREST/Query+Parameters)
- [Response format doc.](https://developers.coveo.com/display/SearchREST/Query+Results).

## Inspiration
Need inspiration? you can see some examples of our sites and implementations here:

* http://saq.coveodemo.com
* http://support.logitech.com
* http://help.salesforce.com

But, don't copy, we will know :)
