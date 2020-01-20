# Coveo Front End Challenge
## The challenge

The SAQ is the government-run liquor store monopoly that we have in Quebec, we indexed the different wines and beers there and made it available through our REST Search API. Don’t be surprised if the prices are high!

The challenge, if you accept it, is about building a search interface based on the Coveo REST API.

See [the documentation section](#documentation)

You can access this api through https://cloudplatform.coveo.com/rest/search with the token we will provide you. This token grants you access to a Coveo index containing different types of alcohols which are sold in [SAQ](saq.com).

## Exemples
#### Searching Amber Ales

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=Bi%C3%A8re%20rousse

#### Searching beers under 10$

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=@tpprixnum%3C10

#### Searching Merlot

    https://cloudplatform.coveo.com/rest/search?access_token=YOUR_TOKEN&q=@tpcepagenomsplitgroup==Merlot

## Documentation

- [Query syntax documentation](http://onlinehelp.coveo.com/en/ces/7.0/User/coveo_query_syntax_reference.htm)
- [REST API documentation](https://developers.coveo.com/display/public/SearchREST/Invoking+the+REST+Search+API)
- [REST parameter documentation](https://developers.coveo.com/display/SearchREST/Query+Parameters)
- [Response format documentation](https://developers.coveo.com/display/SearchREST/Query+Results)

## Inspiration
Need inspiration? you can see some examples of our sites and implementations here:

* http://saq.coveodemo.com
* https://help.salesforce.com

But, don't use or copy the code from those examples or the [Coveo Search UI framework](https://github.com/coveo/search-ui), we will know :)

## Mandatory

- The end result must absolutely be made available publicly on the internet. Heroku, AWS, Microsoft Azure, Google Cloud, etc. all have free tiers you can use. If we have to install and configure your project locally to review the end result, you will be penalized.

## Advice

- **Try to design and implement your solution as you would do for real production code**. Show us how you create clean, maintainable code that does awesome stuff. Build something that we'd be happy to contribute to. This is not a programming contest where dirty hacks win the game.
- Even though you are free to use the framework you want, **do not use the [Coveo Search UI framework](https://github.com/coveo/search-ui)** to complete the challenge.
- Feel free to add more features! Really, we're curious about what you can think of. We'd expect the same if you worked with us.
- Documentation and maintainability is a plus.
- Don't you forget those unit tests.
