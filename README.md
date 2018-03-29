# New York Times Searcher
### By: Novia Lim

## Description:
React-based rendition of the New York Times Article Search application. This assignment requires you to create React components, work with helper functions, and utilize the React mounting lifecycle to query and display articles based on user searches. You'll also use Node, Express and MongoDB so that users can save articles to read later.

## Live Demo: 
https://novialim.herokuapp.com/

## APIs used:
* The New York Times API <https://developer.nytimes.com/>

## Technologies/Libraries Used:
* MongoDB & Mongoose
* Express.js
* React.js
* Node.js
* React Router v4
* Axios

## Deploy to Heroku
* heroku create
* heroku addons:create mongolab
* git add .
* git commit -m "heroku deploy"
* git push heroku master

## heroku default env vars (set by heroku)
* NPM_CONFIG_LOGLEVEL = error
* NPM_CONFIG_PRODUCTION = true
* NODE_VERBOSE = false
* NODE_ENV = production
* NODE_MODULES_CACHE = true
* MONGODB_URI = created in heroku after running heroku addons:create mongolab