![Node.js CI](https://github.com/theairbend3r/poke-zoo/workflows/Node.js%20CI/badge.svg) [![GitHub license](https://img.shields.io/github/license/theairbend3r/poke-zoo)](https://github.com/theairbend3r/poke-zoo/blob/master/LICENSE) [![GitHub issues](https://img.shields.io/github/issues/theairbend3r/poke-zoo)](https://github.com/theairbend3r/poke-zoo/issues)

# PokeZoo

PokeZoo is webapp that enables users to create their own Pokemon collections.

## Tech Stack

This webapp is hosted on `Heroku`.

- Backend - `Node.js`, `Express.js`
- Frontend - `React.js`, `Emotion.js`, `TailwindCSS`
- Database - `MongoDB`
- Authentication - `JsonWebToken`
- API - `pokeAPI`

## Screenshots

### Landing Page

![Landing Page](https://raw.githubusercontent.com/theairbend3r/poke-zoo/master/screenshots/poke-zoo-landing.jpg)

### Home Page

![Home Page](https://raw.githubusercontent.com/theairbend3r/poke-zoo/master/screenshots/poke-zoo-home.png)

### Explore Page

![Explore Page](https://raw.githubusercontent.com/theairbend3r/poke-zoo/master/screenshots/poke-zoo-explore.png)

## App Flow

The app-flow is as follows -

1. Once a user signs-up/logs-in, they will be redirected to the home page that displays their current collection.

2. On the home page, they can create new collections.

3. Once there is at least one collection, Pokemon can be added to it from the explore page.

4. The user can also edit the collection name as well as the Pokemon in it.

5. All collection names have to be unique.

6. Duplicate Pokemon are not allowed in the same collection.
