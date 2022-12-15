# turdle
This repo is associated with the [Refactor Tractor - 1 Day Challenge activity](https://frontend.turing.edu/projects/turdle.html).

## Set Up
1. Fork this repository.
2. Clone the forked repo to your local machine.
3. `cd` into the directory.
4. Open the app with `open index.html`


----- For Post requests associated with this game -------

Must clone down and run turdle-api

https://github.com/turingschool-examples/turdle-api

Clone SSH key: git@github.com:turingschool-examples/turdle-api.git

Then follow the below instructions from the turdle-API README


# turdle-api

This repo is associated with the [Refactor Tractor - 1 Day Challenge activity](https://frontend.turing.edu/projects/module-2/refactor-tractor-1day-turdle.html).

## Set Up

Clone this down, and `cd` into it.  Then run:

`npm install`

`npm start`

## Endpoints

| Description | URL | Method | Required Properties for Request Body | Sample Successful Response |
|----------|-----|--------|---------------------|-----------------|
| Get all words (iteration 2) |`http://localhost:3001/api/v1/words`| GET  | none | An array containing all words |
| Add a new game stat (iteration 4)|`http://localhost:3001/api/v1/games`| POST | `{ solved: <boolean (did they solve the puzzle?)>, guesses: <number (how many guesses did they make?)> }` | `{message: 'Game stats recorded successfully.' }`|
| Get all previous games stats (iteration 4) |`http://localhost:3001/api/v1/games` | GET  | none | An array containing game stats for all previous games (will be empty until you POST)|
