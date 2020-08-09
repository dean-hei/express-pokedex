#Routes for Pokedex

|Address|Type|Description|Final Action|
|---|---|---|---|
|/|GET|Show a list of all pokemon from the API.|render index.ejs
|/pokemon|GET|Show all favorite pokemon from your db|render pokemon.ejs
|/pokemon|POST| Add a new favorite pokemon to your db|redirect to /pokemon
|/pokemon/:id|GET| Show one favorite pokemon| render show.ejs|
|/pokemon/:id|DELETE| (optional) Delete one pokemon from db| redirect to /pokemon