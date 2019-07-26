# Coveo Front End Challenge
## The challenge

Over the years multiple new generations of Pokemon have been added to the Pokedex. There is enough pokemons now that we need to be able to search within the Pokemon database to find different pokemons. Don't worry, the data has already been gathered for you!

The challenge, if you accept it, is about building a search interface based on the Coveo REST API.

See [the documentation section](#documentation)

You can access this api through https://platform.cloud.coveo.com/rest/search/v2 with the token we will provide you. This token grants you access to a Coveo index containing all the different pokemons which are present in the [Pokemon Database](pokemondb.net).

## Exemples
#### Searching for Pikachu

    https://platform.cloud.coveo.com/rest/search/v2?access_token=YOUR_TOKEN&q=pikachu

#### Searching for pokemons of gen 1

    https://platform.cloud.coveo.com/rest/search/v2?access_token=YOUR_TOKEN&q=@generation=1

#### Searching for pokemons of type Steel

    https://platform.cloud.coveo.com/rest/search/v2?access_token=YOUR_TOKEN&q=@type=="Steel"

## Documentation

- [Performing a Query](https://docs.coveo.com/en/1445)
- [Query syntax documentation](https://docs.coveo.com/en/1552)
- [REST parameter documentation](https://docs.coveo.com/en/13)
- [Response format documentation](https://docs.coveo.com/en/1443)

## Inspiration
Need inspiration? you can see some examples of our sites and implementations here:

* https://connect.coveo.com/s/global-search/%40uri#q=Search%20API
* https://help.salesforce.com

But, don't copy the code, we will know :)

## Advice

- **Try to design and implement your solution as you would do for real production code**. Show us how you create clean, maintainable code that does awesome stuff. Build something that we'd be happy to contribute to. This is not a programming contest where dirty hacks win the game.
- Feel free to add more features! Really, we're curious about what you can think of. We'd expect the same if you worked with us.
- Documentation and maintainability is a plus.
- Don't you forget those unit tests.
